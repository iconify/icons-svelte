<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nmvep2rrm"/><path class="jps-wcf_l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:text-wrap-duocolor" {...props}></Icon>
<style>
:global(.jps-wcf_l) {
  d: path("M4 4h16M4 10h13M4 17h4");
}

:global(.nmvep2rrm) {
  stroke-opacity: 0.4;
  d: path("M17 10c4.667 0 4.667 7 0 7h-5m3-3l-3 3l3 3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
