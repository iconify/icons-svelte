<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cpho5swap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:ruler-dimension-line-two-tone" {...props}></Icon>
<style>
:global(.cpho5swap) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 7L2 17M22 7L22 17M2 12L22 12M7 12L7 15M12 12L12 16M17 12L17 15");
}

</style>
