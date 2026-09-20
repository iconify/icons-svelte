<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGNA2wBe4O)" class="r4i437pya"/><path class="rpznh_s1i"/></g><defs><linearGradient id="SVGNA2wBe4O" x1="19" x2="5" y1="12" y2="12" gradientUnits="userSpaceOnUse"><stop class="s6e45k5td"/><stop offset="1" class="a1zkku_qb"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:rune-background" {...props}></Icon>
<style>
:global(.a1zkku_qb) {
  stop-color: var(--svg-color--0cf, #0cf);
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.r4i437pya) {
  d: path("M24 0H0v24h24z");
}

:global(.rpznh_s1i) {
  fill: var(--svg-color--fff, #fff);
  d: path("m5 20l11.211-4.704l-3.546-3.585zM9.117 8.131l3.547 3.58L19 4z");
}

:global(.s6e45k5td) {
  stop-color: var(--svg-color--3f9, #3f9);
}

</style>
