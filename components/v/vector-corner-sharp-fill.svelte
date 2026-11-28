<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="k6j0tvp6u"/><path class="eafvylb4e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:vector-corner-sharp-fill" {...props}></Icon>
<style>
:global(.eafvylb4e) {
  d: path("M10 8L1.812 19.417M14 8L22.187 19.417");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.k6j0tvp6u) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 4H14C14.552 4 15 4.448 15 5V9C15 9.552 14.552 10 14 10H10C9.448 10 9 9.552 9 9V5C9 4.448 9.448 4 10 4H12Z");
  stroke: none;
}

</style>
