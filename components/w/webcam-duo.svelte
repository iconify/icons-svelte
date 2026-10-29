<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/kcytghzxu.css';
import '../../css/p/ppgi3vj8t.css';
import '../../css/o/ozjkdu0on.css';
import '../../css/h/h7focp4gr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="kcytghzxu"/><path class="ppgi3vj8t wm-a"/><path class="ozjkdu0on"/><path class="h7focp4gr wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:webcam-duo" {...props}></Icon>
