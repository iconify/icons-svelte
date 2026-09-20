<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rdvmv8b4c"/><path class="u2c68cx9n"/><path class="hrrcydb2l"/><path class="l7r9aieyp"/><path class="lcu8k5sld"/><path class="yam3-1b2z"/><path class="sl7vxjbhd"/><path class="pt73j1ikv"/><path class="xa3jgydgh"/><path class="g620qibmn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:top-p-duotone-bold" {...props}></Icon>
<style>
:global(.g620qibmn) {
  d: path("M20 17v3");
}

:global(.hrrcydb2l) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 14v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l7r9aieyp) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 12h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lcu8k5sld) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M20 17v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pt73j1ikv) {
  d: path("M15 14v6");
}

:global(.rdvmv8b4c) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sl7vxjbhd) {
  d: path("M10 11v9");
}

:global(.u2c68cx9n) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 11v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xa3jgydgh) {
  d: path("M3 12h9");
}

:global(.yam3-1b2z) {
  d: path("M5 8v12");
}

</style>
