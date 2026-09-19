<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/js3jstb1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="js3jstb1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:signature" {...props}></Icon>
