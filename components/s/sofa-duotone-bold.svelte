<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="anm9_3bvj"/><path class="dem7zwy2d"/><path class="oxq4wubtr"/><path class="zizg2bcko"/><path class="z9gj8gban"/><path class="v6idbfb-b"/><path class="oqj-o0b2r"/><path class="owfn5sxxm"/><path class="x7yzkkbqs"/><path class="xroalcbzh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sofa-duotone-bold" {...props}></Icon>
<style>
:global(.anm9_3bvj) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 19V8h14v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dem7zwy2d) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 14h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.oqj-o0b2r) {
  d: path("M5 14h14");
}

:global(.owfn5sxxm) {
  d: path("M12 8v6");
}

:global(.oxq4wubtr) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 8v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.v6idbfb-b) {
  d: path("M5 19V8h14v11");
}

:global(.x7yzkkbqs) {
  d: path("M2 19v-5h3");
}

:global(.xroalcbzh) {
  d: path("M22 19v-5h-3");
}

:global(.z9gj8gban) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M22 19v-5h-3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zizg2bcko) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 19v-5h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
