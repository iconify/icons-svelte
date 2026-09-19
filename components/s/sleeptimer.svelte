<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="c3f-hsbol"/><path class="mmg_a9bun"/><path class="zkeb72b3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:sleeptimer" {...props}></Icon>
<style>
:global(.c3f-hsbol) {
  cx: 24px;
  cy: 24px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
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

:global(.mmg_a9bun) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.89 19.971l3.23.581l-4.09 4.393l3.23.581m3.029-6.258h5.3l-5.3 8h5.3");
}

:global(.zkeb72b3j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.495 13.793l12.112-2.131l-8.975 19.88l12.112-2.13");
}

</style>
