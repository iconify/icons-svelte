<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uh1j5ublv.css';
import '../../css/d/dzvme4b_s.css';
import '../../css/z/z8__jxbtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="uh1j5ublv"/><circle class="dzvme4b_s"/><circle class="z8__jxbtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:smlight" {...props}></Icon>
