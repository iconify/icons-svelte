<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/i_3sqgb-r.css';
import '../../css/x/x4lq1hb2u.css';
import '../../css/v/v_917cbym.css';
import '../../css/p/py8uhtbvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="i_3sqgb-r"/><path class="wm-a x4lq1hb2u"/><path class="v_917cbym"/><path class="py8uhtbvo wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:tooth-crown-duo" {...props}></Icon>
