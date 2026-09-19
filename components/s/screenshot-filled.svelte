<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oh7ay8b9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oh7ay8b9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:screenshot-filled" {...props}></Icon>
