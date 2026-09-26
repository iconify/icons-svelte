<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="in-kiw_rm"/><path class="lb1jov5wm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:terminal-plus-sharp-two-tone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.in-kiw_rm) {
  d: path("M1.7191 4.7593L9.0001 11L1.6508 17.2993M19 4L19 12M15 8L23 8");
}

:global(.lb1jov5wm) {
  stroke-opacity: 0.4;
  d: path("M19 19L10 19");
}

</style>
