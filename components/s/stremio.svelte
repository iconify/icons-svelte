<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="iruzqnsff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:stremio" {...props}></Icon>
<style>
:global(.iruzqnsff) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.78 24H43.5m-22.66 0H4.5m26.28 0l-9.94 7.43V16.57Zm12.72 0L24 43.5L4.5 24L24 4.5Z");
}

</style>
