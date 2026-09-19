<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="x9rx5gtxs"/><rect class="l-l1v-beh"/></g><path class="l4sgg6xgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:youtube-tv" {...props}></Icon>
<style>
:global(.l-l1v-beh) {
  width: 39px;
  height: 26px;
  x: 4.5px;
  y: 9px;
  rx: 2px;
  ry: 2px;
}

:global(.l4sgg6xgw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.86 22l-9.72-5.596v11.192z");
}

:global(.x9rx5gtxs) {
  d: path("M12 39h24");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
