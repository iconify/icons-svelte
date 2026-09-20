<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="uq2h0y4eh"/><path class="zi5ui6btw"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:waves-background" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.uq2h0y4eh) {
  fill: var(--svg-color--1857f5, #1857f5);
  d: path("M24 0H0v24h24z");
}

:global(.zi5ui6btw) {
  fill: var(--svg-color--fff, #fff);
  d: path("m4 12l8-8l8 8l-8 8z");
}

</style>
