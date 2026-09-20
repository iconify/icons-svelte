<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yam3-1b2z"/><path class="sl7vxjbhd"/><path class="pt73j1ikv"/><path class="xa3jgydgh"/><path class="g620qibmn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:top-p-outline-regular" {...props}></Icon>
<style>
:global(.g620qibmn) {
  d: path("M20 17v3");
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

:global(.xa3jgydgh) {
  d: path("M3 12h9");
}

:global(.yam3-1b2z) {
  d: path("M5 8v12");
}

</style>
