<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ovhu0zb3j"/><circle class="arbnqacnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:voi" {...props}></Icon>
<style>
:global(.arbnqacnn) {
  cx: 38.33px;
  cy: 32.252px;
  r: 4.17px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ovhu0zb3j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 11.755h7.453l7.01 16.77l7.276-16.947h6.92L23.601 36.422H15.97z");
}

</style>
