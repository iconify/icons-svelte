<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-2fhubal.css';
import '../../css/n/n6lshjbtf.css';
import '../../css/x/xtpeb-edw.css';
import '../../css/k/ktlliubjd.css';
import '../../css/w/wl85dh_jk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e-2fhubal"/><path class="n6lshjbtf"/><g class="xtpeb-edw"><path class="ktlliubjd"/><path class="wl85dh_jk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:streets-map-point-bold-duotone" {...props}></Icon>
