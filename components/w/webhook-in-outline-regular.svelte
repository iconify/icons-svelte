<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qw94a7xnn"/><path class="n0hr0gbrt"/><path class="jcxg2bbvb"/><path class="i50mf1njm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:webhook-in-outline-regular" {...props}></Icon>
<style>
:global(.i50mf1njm) {
  d: path("m7 9 3 3 -3 3");
}

:global(.jcxg2bbvb) {
  d: path("M2 12h8");
}

:global(.n0hr0gbrt) {
  d: path("M14 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qw94a7xnn) {
  d: path("M13 6.8a6 6 0 1 1 0 10.4");
}

</style>
