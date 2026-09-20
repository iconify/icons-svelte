<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="w_--dmbrv"/><path class="n4xbfwvxq"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:vsp-background" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.n4xbfwvxq) {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.194 4.774H4l1.034 3.097h2.78l3.928 11.355h3.097L20 4.774h-3.355l-3.355 9.807z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.w_--dmbrv) {
  fill: var(--svg-color--4138ab, #4138ab);
  d: path("M24 0H0v24h24z");
}

</style>
