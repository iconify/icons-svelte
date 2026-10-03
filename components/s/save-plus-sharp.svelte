<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jrzpazkqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:save-plus-sharp" {...props}></Icon>
<style>
:global(.jrzpazkqd) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3L17 3L21 7L21 21L3 21L3 3ZM7 3L7 7L13 7L13 3M12 10L12 18M8 14L16 14");
}

</style>
