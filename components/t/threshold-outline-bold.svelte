<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="d8abqfbpc"/><path class="fhtr4ivmi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:threshold-outline-bold" {...props}></Icon>
<style>
:global(.d8abqfbpc) {
  d: path("M3 11h18");
}

:global(.fhtr4ivmi) {
  d: path("m4 18 6 -6 4 4 6 -6");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
