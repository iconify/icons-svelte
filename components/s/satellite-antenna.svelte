<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ituv_m4-l.css';
import '../../css/c/cth_9lbgc.css';
import '../../css/s/smj2mw7cm.css';
import '../../css/v/vl_m2cbkf.css';
import '../../css/t/tn51lubsq.css';
import '../../css/z/zhxc1wb9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="ituv_m4-l"/><path class="cth_9lbgc"/><path class="smj2mw7cm"/><path class="vl_m2cbkf"/><path class="tn51lubsq"/><path class="zhxc1wb9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:satellite-antenna" {...props}></Icon>
