<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/lp8o_cbul.css';
import '../../css/b/b7h3obcxu.css';
import '../../css/p/pdsejf_aq.css';
import '../../css/c/ck7mqgwyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lp8o_cbul"/><path class="b7h3obcxu"/><path class="pdsejf_aq"/><path class="ck7mqgwyd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:watch-round-broken" {...props}></Icon>
