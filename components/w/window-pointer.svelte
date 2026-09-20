<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vbagabb9t.css';
import '../../css/h/hbp29jb_v.css';
import '../../css/r/rho1w1b5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vbagabb9t"/><path class="hbp29jb_v"/><path class="rho1w1b5b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:window-pointer" {...props}></Icon>
