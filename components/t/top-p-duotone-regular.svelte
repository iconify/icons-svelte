<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c63z0bddk"/><path class="xibn0tbyk"/><path class="szm2jsciq"/><path class="c1sf58bwr"/><path class="mm8jp5bex"/><path class="yam3-1b2z"/><path class="sl7vxjbhd"/><path class="pt73j1ikv"/><path class="xa3jgydgh"/><path class="g620qibmn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:top-p-duotone-regular" {...props}></Icon>
<style>
:global(.c1sf58bwr) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 12h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.c63z0bddk) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g620qibmn) {
  d: path("M20 17v3");
}

:global(.mm8jp5bex) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M20 17v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pt73j1ikv) {
  d: path("M15 14v6");
}

:global(.sl7vxjbhd) {
  d: path("M10 11v9");
}

:global(.szm2jsciq) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 14v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xa3jgydgh) {
  d: path("M3 12h9");
}

:global(.xibn0tbyk) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 11v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yam3-1b2z) {
  d: path("M5 8v12");
}

</style>
