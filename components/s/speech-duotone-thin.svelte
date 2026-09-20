<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yh9u2vb-g"/><path class="r63slnb7d"/><path class="syr202grk"/><path class="a4habeb9x"/><path class="jfpn1_rdc"/><path class="lbz2yq5no"/><path class="el0n_ccnv"/><path class="h7bcztycq"/><path class="cg-q-7bgo"/><path class="om2raabrv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:speech-duotone-thin" {...props}></Icon>
<style>
:global(.a4habeb9x) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cg-q-7bgo) {
  d: path("M16 3v18");
}

:global(.el0n_ccnv) {
  d: path("M8 5v14");
}

:global(.h7bcztycq) {
  d: path("M12 8v8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jfpn1_rdc) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 10v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lbz2yq5no) {
  d: path("M4 9v6");
}

:global(.om2raabrv) {
  d: path("M20 10v4");
}

:global(.r63slnb7d) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.syr202grk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yh9u2vb-g) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
