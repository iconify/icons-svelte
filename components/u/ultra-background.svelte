<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="d41fa4r1t"/><path class="w8lo4tbht"/><path class="k81hkjgyx"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:ultra-background" {...props}></Icon>
<style>
:global(.d41fa4r1t) {
  fill: var(--svg-color--6f3de0, #6f3de0);
  d: path("M0 0h24v24H0z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.k81hkjgyx) {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.4 4v8.001a1.6 1.6 0 1 0 3.2 0V4z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.w8lo4tbht) {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 4v7.999a8 8 0 1 0 16 0V4h-3.2v7.999a4.8 4.8 0 1 1-9.6 0V4z");
}

</style>
