<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9t6jqb7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h9t6jqb7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:user-x-filled" {...props}></Icon>
