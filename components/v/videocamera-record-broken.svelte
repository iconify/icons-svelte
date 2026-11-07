<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/gv_aam95c.css';
import '../../css/e/eym_w8bcv.css';
import '../../css/s/s00zyvb1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="gv_aam95c"/><path class="eym_w8bcv"/><path class="s00zyvb1l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:videocamera-record-broken" {...props}></Icon>
