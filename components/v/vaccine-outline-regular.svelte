<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j9schwodo"/><path class="dbb3ymiyd"/><path class="gcalxb98a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:vaccine-outline-regular" {...props}></Icon>
<style>
:global(.dbb3ymiyd) {
  d: path("M9 7V4h6v3");
}

:global(.gcalxb98a) {
  d: path("M8 13h8");
}

:global(.j9schwodo) {
  d: path("M8 7v13h8V7Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
