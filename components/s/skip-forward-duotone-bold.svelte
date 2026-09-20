<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mg9hj4bbp"/><path class="xv-xt-6hy"/><path class="swmt31b1p"/><path class="gtsw5xviq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:skip-forward-duotone-bold" {...props}></Icon>
<style>
:global(.gtsw5xviq) {
  d: path("M17 5v14");
}

:global(.mg9hj4bbp) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m6 5 7 7 -7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.swmt31b1p) {
  d: path("m6 5 7 7 -7 7");
}

:global(.xv-xt-6hy) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
