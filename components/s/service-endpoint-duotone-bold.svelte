<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="f3--0qe5b"/><path class="h3ct3nrnz"/><path class="uojh1zbuj"/><path class="fg6rngtfi"/><path class="qlnp72b5h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:service-endpoint-duotone-bold" {...props}></Icon>
<style>
:global(.f3--0qe5b) {
  fill: currentColor;
  d: path("M4 11a2 2 0 0 1 2 -2h2.5a2 2 0 0 1 2 2v2.5a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.fg6rngtfi) {
  d: path("M11.5 13.5H14");
}

:global(.h3ct3nrnz) {
  d: path("M4 11a2 2 0 0 1 2 -2h2.5a2 2 0 0 1 2 2v2.5a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

:global(.qlnp72b5h) {
  d: path("M17.5 4v16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.uojh1zbuj) {
  d: path("M11.5 10.5H14");
}

</style>
