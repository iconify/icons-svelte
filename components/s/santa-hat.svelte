<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/fay72gbvh.css';
import '../../css/e/ef66r4bmf.css';
import '../../css/x/xu73cdcji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="fay72gbvh"/><path class="ef66r4bmf"/><path class="wm-a xu73cdcji"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:santa-hat" {...props}></Icon>
