<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="re8wedc-w"/><path class="o4d2wxbke"/><path class="zl6g0h25d"/><path class="jszbb1ext"/><path class="ujgggmb5i"/><path class="cjsg0ab2y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:snow-mountain-duotone-thin" {...props}></Icon>
<style>
:global(.cjsg0ab2y) {
  d: path("M2 20h20");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jszbb1ext) {
  d: path("m2 18 8 -8 4 4 6 -6 2 2");
}

:global(.o4d2wxbke) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m7 13 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.re8wedc-w) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m2 18 8 -8 4 4 6 -6 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ujgggmb5i) {
  d: path("m7 13 3 -3 3 3");
}

:global(.zl6g0h25d) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 20h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
