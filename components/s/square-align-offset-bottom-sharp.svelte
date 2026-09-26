<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="abjx4fbtp"/><path class="rnu_b9b5a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-align-offset-bottom-sharp" {...props}></Icon>
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

:global(.rnu_b9b5a) {
  d: path("M7 16L14 16M8 12L17 12M13 8L17 8");
}

</style>
