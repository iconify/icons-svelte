<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="so3p4h_wv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:triangles-centerline-vertical-sharp" {...props}></Icon>
<style>
:global(.so3p4h_wv) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 1V23M2 12L8 16.22V7.78L2 12ZM22 12L16 16.22V7.78L22 12Z");
}

</style>
