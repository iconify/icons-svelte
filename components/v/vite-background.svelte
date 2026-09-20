<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="w6ns7best"/><path class="f8lf87bdb"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:vite-background" {...props}></Icon>
<style>
:global(.f8lf87bdb) {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 8.2L9 7l-.5 12.5zm6-1.355L20 4.5L8.65 19.355L10 6.85z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.w6ns7best) {
  fill: var(--svg-color--007aff, #007aff);
  d: path("M24 0H0v24h24z");
}

</style>
