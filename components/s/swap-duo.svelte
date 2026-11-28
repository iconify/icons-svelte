<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/j/jt54-o5yg.css';
import '../../css/p/pqgj8yh1x.css';
import '../../css/s/sdu7iab5q.css';
import '../../css/z/zdgxbg6ki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="jt54-o5yg"/><path class="pqgj8yh1x"/><path class="sdu7iab5q"/><path class="zdgxbg6ki"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:swap-duo" {...props}></Icon>
