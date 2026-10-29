<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/ntu-3wbry.css';
import '../../css/v/vg3gqibcj.css';
import '../../css/h/hr7v-vbfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ntu-3wbry"/><path class="vg3gqibcj"/><path class="hr7v-vbfi wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:timer-reset" {...props}></Icon>
