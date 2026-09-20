<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n5v54kp1e"/><path class="pmrzgdder"/><path class="ri2m-q_tv"/><path class="yc_r44biv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:smoke-test-duotone-regular" {...props}></Icon>
<style>
:global(.n5v54kp1e) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pmrzgdder) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m8 14 2.5 -2.5L13 14l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ri2m-q_tv) {
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
}

:global(.yc_r44biv) {
  d: path("m8 14 2.5 -2.5L13 14l2.5 -2.5");
}

</style>
