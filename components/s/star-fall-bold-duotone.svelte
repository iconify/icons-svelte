<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg_tc_thn.css';
import '../../css/l/lvbigfbsb.css';
import '../../css/x/xtpeb-edw.css';
import '../../css/z/z29w3hbal.css';
import '../../css/s/sbj_083-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cg_tc_thn"/><path class="lvbigfbsb"/><g class="xtpeb-edw"><path class="z29w3hbal"/><path class="sbj_083-e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:star-fall-bold-duotone" {...props}></Icon>
