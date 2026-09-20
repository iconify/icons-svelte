<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dy7st-bkc.css';
import '../../css/y/yf-f_bcue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dy7st-bkc"/><path class="yf-f_bcue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tailscale" {...props}></Icon>
