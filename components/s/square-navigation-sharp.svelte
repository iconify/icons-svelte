<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="j0mppdb_k"/><path class="cjpys8beh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-navigation-sharp" {...props}></Icon>
<style>
:global(.cjpys8beh) {
  d: path("M8.5 19.5L12 12.5L15.5 19.5L12 18.6945L8.5 19.5Z");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.j0mppdb_k) {
  d: path("M19 21L21 21L21 3L3 3L3 21L5 21");
}

</style>
