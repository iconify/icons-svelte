<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ynn2b5v5b"/><path class="otsbqtbva"/><path class="ot7dw_bqz"/><path class="tbz--4bgo"/><path class="j7ce0lbql"/><path class="yam3-1b2z"/><path class="sl7vxjbhd"/><path class="pt73j1ikv"/><path class="xa3jgydgh"/><path class="g620qibmn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:top-p-duotone-thin" {...props}></Icon>
<style>
:global(.g620qibmn) {
  d: path("M20 17v3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j7ce0lbql) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 17v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ot7dw_bqz) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 14v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.otsbqtbva) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 11v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pt73j1ikv) {
  d: path("M15 14v6");
}

:global(.sl7vxjbhd) {
  d: path("M10 11v9");
}

:global(.tbz--4bgo) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xa3jgydgh) {
  d: path("M3 12h9");
}

:global(.yam3-1b2z) {
  d: path("M5 8v12");
}

:global(.ynn2b5v5b) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
