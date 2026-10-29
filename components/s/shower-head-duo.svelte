<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/l8e68kzqx.css';
import '../../css/f/fmtboebos.css';
import '../../css/w/w439gnkso.css';
import '../../css/a/afxiy6lsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="l8e68kzqx"/><path class="fmtboebos wm-s"/><path class="w439gnkso wm-a"/><path class="afxiy6lsc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:shower-head-duo" {...props}></Icon>
