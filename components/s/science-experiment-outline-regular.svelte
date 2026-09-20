<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vrp3h-b8z"/><path class="c8uh2gw9u"/><path class="mss3k8l1q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:science-experiment-outline-regular" {...props}></Icon>
<style>
:global(.c8uh2gw9u) {
  d: path("M9 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.mss3k8l1q) {
  d: path("M12.5 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.vrp3h-b8z) {
  d: path("M10 3h4v5.5a6.5 6.5 0 1 1 -4 0Z");
}

</style>
