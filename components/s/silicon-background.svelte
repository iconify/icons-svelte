<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="w6ns7best"/><path class="hvjl2eb6b"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:silicon-background" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.hvjl2eb6b) {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 16v4c3.7 0 7.082-2.029 8.824-5.294l1.882-3.53A5.99 5.99 0 0 1 20 8V4a9.98 9.98 0 0 0-8.824 5.294l-1.882 3.53A5.99 5.99 0 0 1 4 16m12 0h4v4h-4z");
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
