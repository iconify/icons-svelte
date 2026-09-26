<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="abjx4fbtp"/><path class="slpk0qbtn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-align-offset-left-sharp" {...props}></Icon>
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

:global(.slpk0qbtn) {
  d: path("M16 10L16 17M8 7L8 11M12 16L12 7");
}

</style>
