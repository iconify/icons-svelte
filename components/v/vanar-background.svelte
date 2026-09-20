<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ks1sgrb5j"/><path class="capcvizlx"/><path class="ziqu55mir"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:vanar-background" {...props}></Icon>
<style>
:global(.capcvizlx) {
  fill: var(--svg-color--fff, #fff);
  d: path("m13.998 19.2l2-3.602L10 4.8H6L4 8.4h4.003zm4-7.201L20 8.399L17.999 4.8H14l-1.999 3.6H16z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.ks1sgrb5j) {
  fill: var(--svg-color--03d9af, #03d9af);
  d: path("M24 0H0v24h24z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.ziqu55mir) {
  fill: var(--svg-color--fff, #fff);
  d: path("m16 8.4l1.999-3.6H14l-1.999 3.6zm-7.997 0L10 4.8H6L4 8.4z");
}

</style>
