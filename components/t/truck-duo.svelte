<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/f7hl_1dzk.css';
import '../../css/k/k02fzkb_b.css';
import '../../css/w/wjxdsob9d.css';
import '../../css/n/n255akb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="f7hl_1dzk"/><path class="k02fzkb_b wm-a"/><path class="wjxdsob9d wm-a"/><path class="n255akb9d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:truck-duo" {...props}></Icon>
