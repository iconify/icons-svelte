<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/lsy6r8esb.css';
import '../../css/f/fjsedw-yo.css';
import '../../css/c/cfmykrbut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="lsy6r8esb"/><path class="fjsedw-yo wm-a"/><path class="cfmykrbut"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:test-tube-duo" {...props}></Icon>
