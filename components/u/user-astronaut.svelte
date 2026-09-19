<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4d9xybyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="f4d9xybyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:user-astronaut" {...props}></Icon>
