<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="abjx4fbtp"/><path class="s63qubk_z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-align-offset-top-sharp" {...props}></Icon>
<style>
:global(.abjx4fbtp) {
  d: path("M21 3L21 21L3 21L3 3L21 3Z");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.s63qubk_z) {
  d: path("M7 8L14 8M8 12L17 12M13 16L17 16");
}

</style>
