<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="b0icipdtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:shiori-for-genshin" {...props}></Icon>
<style>
:global(.b0icipdtl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 24C33.6 24 24 14.4 24 2.5m0 0C24 14.4 14.4 24 2.5 24M24 45.5C24 33.6 33.6 24 45.5 24m-43 0C14.4 24 24 33.6 24 45.5");
}

:global(.cpk0fnbgt) {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
