<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/g33dr_b1f.css';
import '../../css/n/n2ckldr-l.css';
import '../../css/d/dlvig_bmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="g33dr_b1f"/><path class="n2ckldr-l"/><path class="dlvig_bmn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:rubber-duck" {...props}></Icon>
