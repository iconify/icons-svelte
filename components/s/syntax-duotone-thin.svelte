<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kr1fheb9m"/><path class="upjy9--jw"/><path class="qeku75bzq"/><path class="nt1stnb3c"/><path class="zaau21ski"/><path class="vj8si9dha"/><path class="fa2e7y2tg"/><path class="wfg0vmbgy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:syntax-duotone-thin" {...props}></Icon>
<style>
:global(.fa2e7y2tg) {
  d: path("M4 17h8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kr1fheb9m) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 4 4 8l4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nt1stnb3c) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 17h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qeku75bzq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 17h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.upjy9--jw) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16 4 4 4 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vj8si9dha) {
  d: path("m16 4 4 4 -4 4");
}

:global(.wfg0vmbgy) {
  d: path("M15 17h5");
}

:global(.zaau21ski) {
  d: path("M8 4 4 8l4 4");
}

</style>
