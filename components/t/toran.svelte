<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/lf-l1gbwa.css';
import '../../css/u/u3u6a8b0i.css';
import '../../css/i/iieeedbrs.css';
import '../../css/n/n6y6-qb3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="lf-l1gbwa"/><path class="u3u6a8b0i wm-a"/><path class="iieeedbrs"/><path class="n6y6-qb3g wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:toran" {...props}></Icon>
