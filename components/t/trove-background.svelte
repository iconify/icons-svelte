<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGbl9lHdVB)" class="r4i437pya"/><path class="n-mcy7b8q"/></g><defs><linearGradient id="SVGbl9lHdVB" x1="11.999" x2="11.999" y1="4.244" y2="19.749" gradientUnits="userSpaceOnUse"><stop class="wnzh9-bom"/><stop offset="1" class="ius1tzbmn"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:trove-background" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.ius1tzbmn) {
  stop-color: var(--svg-color--746e89, #746e89);
}

:global(.n-mcy7b8q) {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.575 18.399a2.52 2.52 0 0 0 2.236 1.35h1.93c.945 0 1.55-1 1.115-1.836L13.114 4.925a1.26 1.26 0 0 0-2.23 0L4.142 17.913a1.255 1.255 0 0 0 1.115 1.836h1.716c.905 0 1.745-.49 2.19-1.275l1.906-3.371c-.3-.17-.55-.42-.72-.726a2 2 0 1 1 3.3 0a1.9 1.9 0 0 1-.775.756z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.r4i437pya) {
  d: path("M24 0H0v24h24z");
}

:global(.wnzh9-bom) {
  stop-color: var(--svg-color--6036ef, #6036ef);
}

</style>
