<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/e/e77ebfb5e.css';
import '../../css/u/uj7-h_b4y.css';
import '../../css/b/bqf3fdtgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="e77ebfb5e"/><path class="uj7-h_b4y"/><path class="bqf3fdtgc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:square-search" {...props}></Icon>
