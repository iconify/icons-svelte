<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="bzn9l8baq"/><path class="w79rg6i4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:spacehey-mobile" {...props}></Icon>
<style>
:global(.bzn9l8baq) {
  cx: 32.419px;
  cy: 14.064px;
  r: 4.167px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.w79rg6i4j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.59 38.103h13.52V25.397s-2.225-4.762-6.55-4.774c-4.56-.012-6.97 4.774-6.97 4.774zm-1.963-22.248l-12.485.002c-4.02 0-6.541 13.082 4.451 12.87c7.175-.138 7.955-4.159 7.955-5.323z");
}

</style>
