<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmfou0x8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="wmfou0x8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:user-graduate" {...props}></Icon>
