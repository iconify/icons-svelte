<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGvewCrcrF)" class="r4i437pya"/><path class="c7s27tzoa"/></g><defs><linearGradient id="SVGvewCrcrF" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="dsv9qhbgl"/><stop offset="1" class="o53tdccfe"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:tonic-background" {...props}></Icon>
<style>
:global(.c7s27tzoa) {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.533 4h9.6v4.267h-9.6zM15.2 4h4.266v4.267H15.2zm-1.067 5.333H9.866V20h4.267z");
}

:global(.dsv9qhbgl) {
  stop-color: var(--svg-color--000d34, #000d34);
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.o53tdccfe) {
  stop-color: var(--svg-color--42243d, #42243d);
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.r4i437pya) {
  d: path("M24 0H0v24h24z");
}

</style>
