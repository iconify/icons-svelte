<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGedAOvdxE)" class="r4i437pya"/><path class="pm0-wj-hq"/><path class="awu4lrbvd"/></g><defs><linearGradient id="SVGedAOvdxE" x1="19.2" x2="4.533" y1="12.714" y2="12.714" gradientUnits="userSpaceOnUse"><stop class="u6779ih_x"/><stop offset="1" class="jtoax-zqe"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:unix-background" {...props}></Icon>
<style>
:global(.awu4lrbvd) {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 15.734a2.667 2.667 0 1 0 0-5.334a2.667 2.667 0 0 0 0 5.334");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.jtoax-zqe) {
  stop-color: var(--svg-color--7d00bc, #7d00bc);
}

:global(.pm0-wj-hq) {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 20c-4.736 0-7.467-2.459-7.467-7.259V4H8.8v8.597c0 2.134.827 3.67 3.2 3.67c2.363 0 3.2-1.558 3.2-3.67V4h4.267v8.741c0 4.8-2.731 7.259-7.467 7.259");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.r4i437pya) {
  d: path("M24 0H0v24h24z");
}

:global(.u6779ih_x) {
  stop-color: var(--svg-color--bd106a, #bd106a);
}

</style>
