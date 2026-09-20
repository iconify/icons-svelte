<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/j/jd46t2bod.css';
import '../../css/v/vew6e5s0g.css';
import '../../css/u/urm07pk_y.css';
import '../../css/s/s27xxkb2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="jd46t2bod"/><path class="vew6e5s0g"/><path class="urm07pk_y"/><path class="s27xxkb2y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:video-meeting-monitor-webcam" {...props}></Icon>
