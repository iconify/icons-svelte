<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zl0m38bil"/><path class="tvejqcbad"/><path class="rfwgx-bjs"/><path class="ty0lyg29l"/><path class="jof7c9fpk"/><path class="ldq326b0y"/><path class="m-p3hbclp"/><path class="vu9j-xb3y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:settings-duotone-bold" {...props}></Icon>
<style>
:global(.jof7c9fpk) {
  d: path("M4 9h16");
}

:global(.ldq326b0y) {
  d: path("M9 7v4");
}

:global(.m-p3hbclp) {
  d: path("M4 15h16");
}

:global(.rfwgx-bjs) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 15h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tvejqcbad) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 7v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ty0lyg29l) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 13v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vu9j-xb3y) {
  d: path("M15 13v4");
}

:global(.zl0m38bil) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 9h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
