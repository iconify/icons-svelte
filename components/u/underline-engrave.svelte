<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/t776lnp7b.css';
import '../../css/z/z3rf84bgx.css';
import '../../css/k/k61rxtjwk.css';
import '../../css/h/h-pfqgbzl.css';
import '../../css/d/dc6exx_io.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="t776lnp7b wm-k"/><path class="wm-a z3rf84bgx"/><path class="k61rxtjwk wm-shadow"/><path class="h-pfqgbzl wm-k"/><path class="dc6exx_io wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:underline-engrave" {...props}></Icon>
