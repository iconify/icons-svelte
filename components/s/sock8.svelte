<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qk3j65bku"/><path class="gh1n5fb0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:sock8" {...props}></Icon>
<style>
:global(.gh1n5fb0j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.125 19.125V43.5l16.25-24.375z");
}

:global(.qk3j65bku) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.625 4.5h16.25v24.375h-16.25z");
}

</style>
