<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGm65v0bbb)" class="r4i437pya"/><path class="ok1ms_lmr"/></g><defs><linearGradient id="SVGm65v0bbb" x1="4.25" x2="19.75" y1="20" y2="20" gradientUnits="userSpaceOnUse"><stop class="a1zkku_qb"/><stop offset="1" class="s6e45k5td"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:tgt-background" {...props}></Icon>
<style>
:global(.a1zkku_qb) {
  stop-color: var(--svg-color--0cf, #0cf);
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.ok1ms_lmr) {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.735 11.71L8.81 8.13L19.75 4zm3.93 3.585L4.25 20l8.485-8.29z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.r4i437pya) {
  d: path("M24 0H0v24h24z");
}

:global(.s6e45k5td) {
  stop-color: var(--svg-color--3f9, #3f9);
}

</style>
