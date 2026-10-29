<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/gl4-s_bqc.css';
import '../../css/a/arnw8bb-h.css';
import '../../css/a/a7not2p8q.css';
import '../../css/x/xe51jsboi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="gl4-s_bqc"/><path class="arnw8bb-h wm-a"/><path class="a7not2p8q"/><path class="wm-a xe51jsboi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:text-cursor-input-duo" {...props}></Icon>
