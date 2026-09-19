<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/r/rr5jdpbbl.css';
import '../../css/e/e56qc54my.css';
import '../../css/t/t64jy78oe.css';
import '../../css/x/x677y-bul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="rr5jdpbbl"/><circle class="e56qc54my"/><path class="t64jy78oe"/><path class="x677y-bul"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:tractor" {...props}></Icon>
