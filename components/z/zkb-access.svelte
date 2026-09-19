<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="olytz1bis"/><path class="ilp10npaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:zkb-access" {...props}></Icon>
<style>
:global(.ilp10npaa) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.187 23.756H43.5m-9.727 5.15v-5.15m9.727 0v9.331");
}

:global(.olytz1bis) {
  cx: 13.344px;
  cy: 23.756px;
  r: 8.844px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
