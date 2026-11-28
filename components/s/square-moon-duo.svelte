<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hazsxsbyl.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/e/e77ebfb5e.css';
import '../../css/j/j1h113bom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hazsxsbyl secondary"/><g class="dt0cm9dhy primary"><path class="e77ebfb5e"/><path class="j1h113bom"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:square-moon-duo" {...props}></Icon>
