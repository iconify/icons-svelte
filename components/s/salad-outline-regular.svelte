<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k187sabpz"/><path class="kpavcn10r"/><path class="n5cv_rbxc"/><path class="o7aygz06s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:salad-outline-regular" {...props}></Icon>
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

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o7aygz06s) {
  d: path("m11 11 4 -4 4 4");
}

</style>
