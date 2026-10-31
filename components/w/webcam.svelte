<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/j/jg90w6vjv.css';
import '../../css/q/qpf4a4i9g.css';
import '../../css/m/myo1y_bfp.css';
import '../../css/h/h8zyowbmm.css';
import '../../css/o/omr02s6jr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="jg90w6vjv wm-shadow"/><path class="qpf4a4i9g wm-shadow"/><path class="myo1y_bfp"/><path class="h8zyowbmm"/><path class="omr02s6jr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:webcam" {...props}></Icon>
