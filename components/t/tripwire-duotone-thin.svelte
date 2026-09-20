<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p7air0nan"/><path class="l_-i6ebvx"/><path class="g_dhy0xii"/><path class="ctozbfb3g"/><path class="hqnawqvnx"/><path class="s-etibjpa"/><path class="cwy6p7vpw"/><path class="urilmibxp"/><path class="c_jwtcbat"/><path class="v7xfanbfw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tripwire-duotone-thin" {...props}></Icon>
<style>
:global(.c_jwtcbat) {
  d: path("M12 3.5V6");
}

:global(.ctozbfb3g) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 13h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cwy6p7vpw) {
  d: path("M20 10v10");
}

:global(.g_dhy0xii) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 10v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hqnawqvnx) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 3.5V6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l_-i6ebvx) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 10v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.p7air0nan) {
  fill: currentColor;
  d: path("M11 8.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s-etibjpa) {
  d: path("M4 10v10");
}

:global(.urilmibxp) {
  d: path("M4 13h16");
}

:global(.v7xfanbfw) {
  d: path("M11 8.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
