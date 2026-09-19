<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="anhokz9eq"/><path class="e4xbwufyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:sesame" {...props}></Icon>
<style>
:global(.anhokz9eq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.47 4.5a12.138 12.138 0 0 0 0 24.277h7.196V4.5Z");
}

:global(.e4xbwufyj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.334 16.638V43.5h7.196a12.137 12.137 0 0 0 12.136-12.138V16.638");
}

</style>
