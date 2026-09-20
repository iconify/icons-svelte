<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e77gki8ci"/><path class="jdqylbbkf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:warehouse-pick-outline-regular" {...props}></Icon>
<style>
:global(.e77gki8ci) {
  d: path("M2 20V10l3 -3h14l3 3v10");
}

:global(.jdqylbbkf) {
  d: path("m9 14 2 2 4 -4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
