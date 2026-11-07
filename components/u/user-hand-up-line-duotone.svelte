<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/cxv0e2blx.css';
import '../../css/i/i5bv225ul.css';
import '../../css/d/dtl23o_xq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="cxv0e2blx"/><path class="i5bv225ul"/><circle class="dtl23o_xq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:user-hand-up-line-duotone" {...props}></Icon>
