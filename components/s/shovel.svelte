<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/r/rd6xl6bok.css';
import '../../css/s/sq0pxym8x.css';
import '../../css/v/vn1s0qnsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="rd6xl6bok"/><path class="sq0pxym8x"/><path class="vn1s0qnsw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:shovel" {...props}></Icon>
