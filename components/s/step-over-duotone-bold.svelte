<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h2sq3fbpa"/><path class="mbte3jbps"/><path class="uznwvsb7r"/><path class="xyj-l9cjp"/><path class="ilnpzmblt"/><path class="b1o8mue8c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:step-over-duotone-bold" {...props}></Icon>
<style>
:global(.b1o8mue8c) {
  d: path("m15 11 3 3 3 -3");
}

:global(.h2sq3fbpa) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ilnpzmblt) {
  d: path("M6 14a6 6 0 0 1 12 0");
}

:global(.mbte3jbps) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 14a6 6 0 0 1 12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.uznwvsb7r) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 11 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xyj-l9cjp) {
  d: path("M3 18h18");
}

</style>
