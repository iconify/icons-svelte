<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="bau9ghf8a"/><path class="vx1nhutmp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:subscript-sharp-two-tone" {...props}></Icon>
<style>
:global(.bau9ghf8a) {
  stroke-opacity: 0.4;
  d: path("M1.7704 3.6375L12 16L12.2999 16.3625M12.2998 3.6402L12 4L2 16L1.7681 16.2783");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.vx1nhutmp) {
  d: path("M16.4323 15.3965L16.75 15.1L19 13L19 20M15 20L23 20");
}

</style>
