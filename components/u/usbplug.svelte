<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csg4-9uxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="csg4-9uxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:usbplug" {...props}></Icon>
