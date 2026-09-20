<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oscmqi7_r"/><path class="z9ittvbis"/><path class="oh3t_sdfd"/><path class="b4nrz0b6r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tab-close-outline-regular" {...props}></Icon>
<style>
:global(.b4nrz0b6r) {
  d: path("m20.5 10.5 -5 5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oh3t_sdfd) {
  d: path("m15.5 10.5 5 5");
}

:global(.oscmqi7_r) {
  d: path("M2 19V9l2 -2h6l2 2v10");
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

</style>
