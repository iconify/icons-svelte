<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cbupdhliu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:wink-video" {...props}></Icon>
<style>
:global(.cbupdhliu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.644 24.001L7.931 13.288L18.644 2.575L40.069 24L18.644 45.425L7.931 34.712z");
}

</style>
