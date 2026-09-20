<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="t_6yxgb6t"/><path class="qrks0gjlh"/><path class="zgd6i_pis"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:wallet-3-background" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.qrks0gjlh) {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.53 4H20v16H4v-5.172l10.502 2.987a.507.507 0 0 0 .646-.486l.026-6.218a.507.507 0 0 1 .684-.473l2.291.852a.507.507 0 0 0 .675-.568z");
}

:global(.t_6yxgb6t) {
  fill: var(--svg-color--6286ff, #6286ff);
  d: path("M24 0H0v24h24z");
}

:global(.zgd6i_pis) {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.92 4H4v4.545l7.635 3.776a.508.508 0 0 0 .718-.337l.761-3.193a.507.507 0 0 1 .642-.367l3.033.926a.507.507 0 0 0 .652-.54z");
}

</style>
