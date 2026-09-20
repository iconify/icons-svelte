<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vfo57uyzf"/><path class="pemn838wn"/><path class="q2fp4ccin"/><path class="ia4sldbfw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:support-group-outline-regular" {...props}></Icon>
<style>
:global(.ia4sldbfw) {
  d: path("M3 21a9 9 0 0 1 18 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pemn838wn) {
  d: path("M9 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.q2fp4ccin) {
  d: path("M15 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.vfo57uyzf) {
  d: path("M3 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
