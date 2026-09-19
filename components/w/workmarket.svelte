<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="u8k1adbgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:workmarket" {...props}></Icon>
<style>
:global(.u8k1adbgc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.5 17l5.571 14l5.572-14l5.571 14l5.572-14l5.571 14l5.572-14l5.57 14");
}

</style>
