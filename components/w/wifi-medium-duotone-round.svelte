<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cy4-vcchj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:wifi-medium-duotone-round" {...props}></Icon>
<style>
:global(.cy4-vcchj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 19h.01M9 16c1.427-2.14 4.573-2.14 6 0m-9-3c3.123-3.747 8.878-3.747 12 0");
}

</style>
