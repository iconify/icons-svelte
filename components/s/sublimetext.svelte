<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-htnbcov.css';
import '../../css/h/h79w7ebun.css';
import '../../css/y/y15y19baw.css';
import '../../css/a/ab_vj2bdb.css';
import '../../css/q/q5w-gwbjp.css';
import '../../css/b/bytekl23q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<defs><linearGradient id="SVGLDVpacBn" x1="69.035" x2="77.473" y1="107.999" y2="79.786" gradientUnits="userSpaceOnUse"><stop offset="0" class="h-htnbcov"/><stop offset=".53" class="h79w7ebun"/><stop offset="1" class="y15y19baw"/></linearGradient></defs><path fill="url(#SVGLDVpacBn)" class="ab_vj2bdb"/><path class="q5w-gwbjp"/><path class="bytekl23q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:sublimetext" {...props}></Icon>
