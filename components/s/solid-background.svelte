<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG6xy4Mb7c)" class="r4i437pya"/><path class="u8550mp4m"/></g><defs><linearGradient id="SVG6xy4Mb7c" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="dltdc5rjj"/><stop offset="1" class="oakdr_dxm"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:solid-background" {...props}></Icon>
<style>
:global(.dltdc5rjj) {
  stop-color: var(--svg-color--00c0d6, #00c0d6);
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.oakdr_dxm) {
  stop-color: var(--svg-color--10f9db, #10f9db);
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.r4i437pya) {
  d: path("M24 0H0v24h24z");
}

:global(.u8550mp4m) {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 20a8 8 0 1 0 0-16a8 8 0 0 0 0 16");
}

</style>
