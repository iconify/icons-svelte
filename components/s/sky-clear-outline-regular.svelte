<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="f2s0o7o5j"/><path class="f59axuhhu"/><path class="ldfbmybql"/><path class="pcl5pkbcw"/><path class="votyijv0m"/><path class="z9ittvbis"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sky-clear-outline-regular" {...props}></Icon>
<style>
:global(.f2s0o7o5j) {
  d: path("M7.5 9a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

:global(.f59axuhhu) {
  d: path("M4.5 4.5 7 7");
}

:global(.ldfbmybql) {
  d: path("M19.5 4.5 17 7");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pcl5pkbcw) {
  d: path("M2 9h3");
}

:global(.votyijv0m) {
  d: path("M19 9h3");
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

</style>
