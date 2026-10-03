<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="dl_n0-bws"/><path class="sqq2n-3lj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-arrow-out-up-right-sharp-two-tone" {...props}></Icon>
<style>
:global(.dl_n0-bws) {
  stroke-opacity: 0.4;
  d: path("M10 7L3 7L3 21L17 21L17 14");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sqq2n-3lj) {
  d: path("M12.7071 11.2929L20.8536 3.1464M12 3L21 3L21 12");
}

</style>
