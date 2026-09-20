<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pc4ntbcgf"/><path class="yix-58bnj"/><path class="moha5wbmp"/><path class="l0eqi9cfe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sensitive-category-duotone-regular" {...props}></Icon>
<style>
:global(.l0eqi9cfe) {
  d: path("m12 9 3 3 -3 3 -3 -3Z");
}

:global(.moha5wbmp) {
  d: path("M22 12a12.5 12.5 0 0 1 -20 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pc4ntbcgf) {
  fill: currentColor;
  d: path("m12 9 3 3 -3 3 -3 -3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.yix-58bnj) {
  d: path("M2 12a12.5 12.5 0 0 1 20 0");
}

</style>
