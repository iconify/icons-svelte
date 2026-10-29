<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/o9p57-x7x.css';
import '../../css/l/ldmenhbkx.css';
import '../../css/c/c-t_59bnx.css';
import '../../css/t/t_g_x1biv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="o9p57-x7x"/><path class="ldmenhbkx wm-a"/><path class="c-t_59bnx wm-a"/><path class="t_g_x1biv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:users-round-duo" {...props}></Icon>
