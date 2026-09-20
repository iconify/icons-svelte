<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="lgln19b5l"/><path class="r6ze1cb0r"/><path class="a4e0i3bzn"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:xet-background" {...props}></Icon>
<style>
:global(.a4e0i3bzn) {
  fill: var(--svg-color--fff, #fff);
  d: path("m12.61 9.02l2.42-3.52h3.975L14.57 12L19 18.5h-3.99l-2.165-3.16l-.39.45L14.7 19H20l-4.72-7L20 5h-5.3l-2.465 3.53z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.lgln19b5l) {
  fill: var(--svg-color--0681ff, #0681ff);
  d: path("M24 0H0v24h24z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.r6ze1cb0r) {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.3 5H4l4.675 7L4 19h5.3l4.99-7z");
}

</style>
