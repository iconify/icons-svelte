<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/l5s0pfbji.css';
import '../../css/d/dtl23o_xq.css';
import '../../css/g/gaihcltbf.css';
import '../../css/r/rdnf-acrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="l5s0pfbji"/><circle class="dtl23o_xq"/><path class="gaihcltbf"/><path class="rdnf-acrq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:user-cross-rounded-line-duotone" {...props}></Icon>
