<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qn4j5jb3u"/><path class="q5571yuok"/><path class="sa-fbkf8q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:table-rows-remove-above-duotone" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q5571yuok) {
  fill: currentColor;
  d: path("M2 12L22 12L22 19C22 21.2091 20.2091 23 18 23L6 23C3.7909 23 2 21.2091 2 19L2 12Z");
  stroke: none;
}

:global(.qn4j5jb3u) {
  stroke-opacity: 0.4;
  d: path("M5 4.1716C3.8014 4.5954 3 5.7287 3 7L3 13M21 13L21 7C21 5.7287 20.1986 4.5954 19 4.1716");
}

:global(.sa-fbkf8q) {
  d: path("M9 2L15 8M15 2L9 8");
}

</style>
