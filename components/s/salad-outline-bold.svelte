<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k187sabpz"/><path class="kpavcn10r"/><path class="n5cv_rbxc"/><path class="o7aygz06s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:salad-outline-bold" {...props}></Icon>
<style>
:global(.k187sabpz) {
  d: path("M2 11h20");
}

:global(.kpavcn10r) {
  d: path("M21 11a9 9 0 0 1 -18 0");
}

:global(.n5cv_rbxc) {
  d: path("m5 11 4 -4 4 4");
}

:global(.o7aygz06s) {
  d: path("m11 11 4 -4 4 4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
