<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zyaro_brf"/><path class="zrasp8b3z"/><path class="psjx1r07k"/><path class="vsyw0vqqg"/><path class="gvxpcrbdq"/><path class="v6idbfb-b"/><path class="oqj-o0b2r"/><path class="owfn5sxxm"/><path class="x7yzkkbqs"/><path class="xroalcbzh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sofa-duotone-thin" {...props}></Icon>
<style>
:global(.gvxpcrbdq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M22 19v-5h-3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oqj-o0b2r) {
  d: path("M5 14h14");
}

:global(.owfn5sxxm) {
  d: path("M12 8v6");
}

:global(.psjx1r07k) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 8v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.v6idbfb-b) {
  d: path("M5 19V8h14v11");
}

:global(.vsyw0vqqg) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 19v-5h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x7yzkkbqs) {
  d: path("M2 19v-5h3");
}

:global(.xroalcbzh) {
  d: path("M22 19v-5h-3");
}

:global(.zrasp8b3z) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 14h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zyaro_brf) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 19V8h14v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
