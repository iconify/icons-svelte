<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="abjx4fbtp"/><path class="watbwr0lo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-align-offset-right-sharp" {...props}></Icon>
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

:global(.watbwr0lo) {
  d: path("M16 7L16 14M8 13L8 17M12 17L12 8");
}

</style>
