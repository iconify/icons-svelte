<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p91dptbzm"/><path class="w2ms_j_hn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:text-wrap-two-tone" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p91dptbzm) {
  stroke-opacity: 0.4;
  d: path("M3 3H21M3 15H8M3 21H15");
}

:global(.w2ms_j_hn) {
  d: path("M3 9H18C19.6569 9 21 10.3431 21 12C21 13.6569 19.6569 15 18 15H12M14 13L12 15L14 17");
}

</style>
