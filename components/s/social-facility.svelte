<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usb26tbjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="usb26tbjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:social-facility" {...props}></Icon>
