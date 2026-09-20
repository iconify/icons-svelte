<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d1wv1pbpc"/><path class="bi4el8ygv"/><path class="uwx4n6b8m"/><path class="zlcluhetu"/><path class="w1fvqnt0l"/><path class="gtsw5xviq"/><path class="nkj1px1_f"/><path class="cfv90ubkl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:scroll-agent-duotone-thin" {...props}></Icon>
<style>
:global(.bi4el8ygv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cfv90ubkl) {
  d: path("M14.5 16.5 17 19l2.5 -2.5");
}

:global(.d1wv1pbpc) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9.69 8.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gtsw5xviq) {
  d: path("M17 5v14");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nkj1px1_f) {
  d: path("M14.5 7.5 17 5l2.5 2.5");
}

:global(.uwx4n6b8m) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14.5 7.5 17 5l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.w1fvqnt0l) {
  d: path("M9.69 8.37a4 4 0 1 1 -3.38 0");
}

:global(.zlcluhetu) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14.5 16.5 17 19l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
