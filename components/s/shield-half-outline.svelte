<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iy-sd1yvj.css';
import '../../css/p/pix652y1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iy-sd1yvj"/><path class="pix652y1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:shield-half-outline" {...props}></Icon>
