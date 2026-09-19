<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2pjm-rrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r2pjm-rrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:ruler-combined" {...props}></Icon>
