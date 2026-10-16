<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr71bdctn.css';
import '../../css/k/kezkawjrn.css';
import '../../css/c/czpegmbjb.css';
import '../../css/s/ss_828btg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wr71bdctn"/><path class="kezkawjrn"/><path class="czpegmbjb"/><path class="ss_828btg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-cooker-48" {...props}></Icon>
