<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yxziwvc_g"/><path class="cm2xziy9r"/><path class="bswhpn18z"/><path class="hpy_80lju"/><path class="kgzfjfb2m"/><path class="mglly3fuq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:stack-trace-duotone-thin" {...props}></Icon>
<style>
:global(.bswhpn18z) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 10v3h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cm2xziy9r) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 7v10h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hpy_80lju) {
  d: path("M3 3v18h8");
}

:global(.kgzfjfb2m) {
  d: path("M9 7v10h6");
}

:global(.mglly3fuq) {
  d: path("M15 10v3h4");
}

:global(.yxziwvc_g) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 3v18h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
