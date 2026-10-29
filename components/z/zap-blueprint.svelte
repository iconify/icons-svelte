<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/k/kp5oeubfs.css';
import '../../css/x/x_vd_wbdc.css';
import '../../css/r/rbzq4bjzv.css';
import '../../css/m/mkwu02oja.css';
import '../../css/e/e3772k5pm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="kp5oeubfs wm-deco"/><path class="wm-deco x_vd_wbdc"/><path class="rbzq4bjzv wm-deco"/><path class="mkwu02oja"/><path class="e3772k5pm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:zap-blueprint" {...props}></Icon>
