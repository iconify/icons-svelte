<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/k8joftj-v.css';
import '../../css/v/vffpfaczr.css';
import '../../css/n/nzuptnbav.css';
import '../../css/p/pxm2isbes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="k8joftj-v"/><path class="vffpfaczr"/><path class="nzuptnbav"/><path class="pxm2isbes"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:tape-measure" {...props}></Icon>
