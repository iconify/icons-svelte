<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i_buofb4t"/><path class="k9ge62i2y"/><path class="daiaqmbao"/><path class="owl5xpbgo"/><path class="zl6g0h25d"/><path class="j3fr8pubv"/><path class="lmi4eb-oe"/><path class="igyz-cc5b"/><path class="zhhqt74pq"/><path class="cjsg0ab2y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sandstorm-duotone-thin" {...props}></Icon>
<style>
:global(.cjsg0ab2y) {
  d: path("M2 20h20");
}

:global(.daiaqmbao) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 20a5 5 0 0 1 10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i_buofb4t) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 6h15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.igyz-cc5b) {
  d: path("M3 20a5 5 0 0 1 10 0");
}

:global(.j3fr8pubv) {
  d: path("M3 6h15");
}

:global(.k9ge62i2y) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 10h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lmi4eb-oe) {
  d: path("M5 10h16");
}

:global(.owl5xpbgo) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 20a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zhhqt74pq) {
  d: path("M13 20a4 4 0 0 1 8 0");
}

:global(.zl6g0h25d) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 20h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
