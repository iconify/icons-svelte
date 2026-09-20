<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="errpswf4y"/><path clip-rule="evenodd" class="q4i2uutea"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:vpad-background" {...props}></Icon>
<style>
:global(.errpswf4y) {
  fill: var(--svg-color--68ffd2, #68ffd2);
  d: path("M24 0H0v24h24z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.q4i2uutea) {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("m4 5l8 14l8-14zm4.42 2.5l1.255 2.34L8.5 11.5h2.135L12 14l3.425-6.5z");
}

</style>
