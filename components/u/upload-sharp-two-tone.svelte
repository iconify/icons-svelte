<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="rwjzogb5q"/><path class="p3xqt9u1y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:upload-sharp-two-tone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p3xqt9u1y) {
  d: path("M4 17L4 21L20 21L20 17");
}

:global(.rwjzogb5q) {
  stroke-opacity: 0.4;
  d: path("M12 15L12 3M7.7071 7.2929L12 3L16.2929 7.2929");
}

</style>
