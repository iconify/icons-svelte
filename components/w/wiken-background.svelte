<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="h2n3jjbkq"/><path class="ds595yf1s"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:wiken-background" {...props}></Icon>
<style>
:global(.ds595yf1s) {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 8.38h16l-5.867 7.239L12 13.032L9.867 15.62zm10.149 5.334l3.756-4.19H6.095l3.756 4.19L12 11.428z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.h2n3jjbkq) {
  fill: var(--svg-color--474747, #474747);
  d: path("M24 0H0v24h24z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
