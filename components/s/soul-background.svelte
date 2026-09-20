<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ecs6oihuw"/><path class="fc_psjb2c"/><path class="ip36-bb_a"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:soul-background" {...props}></Icon>
<style>
:global(.ecs6oihuw) {
  fill: var(--svg-color--ff2e79, #ff2e79);
  d: path("M24 0H0v24h24z");
}

:global(.fc_psjb2c) {
  fill: var(--svg-color--f9f9f9, #f9f9f9);
  d: path("M17.164 9.199H6.858c-1.566 0-2.836 1.255-2.836 2.803s1.27 2.803 2.836 2.803h10.306c1.566 0 2.835-1.255 2.835-2.803S18.73 9.2 17.164 9.2");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.ip36-bb_a) {
  fill: var(--svg-color--f9f9f9, #f9f9f9);
  d: path("M9.996 4.829L4.832 9.972a2.82 2.82 0 0 0 0 4.002a2.85 2.85 0 0 0 4.018 0l5.164-5.143a2.82 2.82 0 0 0 0-4.002a2.85 2.85 0 0 0-4.018 0m5.154 5.197l-5.164 5.143a2.82 2.82 0 0 0 0 4.002a2.85 2.85 0 0 0 4.018 0l5.164-5.143a2.82 2.82 0 0 0 0-4.002a2.85 2.85 0 0 0-4.018 0");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
