<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qa1h-jbfk"/><path class="ixnx5hkex"/><path class="yazo7scbq"/><path class="g7c6_g9qq"/><path class="hmv-0nk4s"/><path class="h1h08f6go"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:shower-head-duotone-bold" {...props}></Icon>
<style>
:global(.g7c6_g9qq) {
  d: path("M9 12v3");
}

:global(.h1h08f6go) {
  d: path("M15 12v3");
}

:global(.hmv-0nk4s) {
  d: path("M12 12v5");
}

:global(.ixnx5hkex) {
  d: path("M6 6h12l-3 3H9Z");
}

:global(.qa1h-jbfk) {
  fill: currentColor;
  d: path("M6 6h12l-3 3H9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.yazo7scbq) {
  d: path("M12 3v3");
}

</style>
