<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/k/kdor8uosb.css';
import '../../css/f/fv_0-tisf.css';
import '../../css/a/ayhs6pbko.css';
import '../../css/o/oeebofbrq.css';
import '../../css/f/folfl_fvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="kdor8uosb wm-deco"/><path class="fv_0-tisf wm-deco"/><path class="ayhs6pbko wm-deco"/><path class="oeebofbrq wm-k"/><path class="folfl_fvi wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:snow-globe-blueprint" {...props}></Icon>
