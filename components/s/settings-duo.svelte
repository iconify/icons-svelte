<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/x/xjy703kxm.css';
import '../../css/h/hbi8hhkfx.css';
import '../../css/b/bp8ecnj5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="xjy703kxm"/><path class="hbi8hhkfx wm-a"/><path class="bp8ecnj5l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:settings-duo" {...props}></Icon>
