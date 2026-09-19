<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="bpwg77ejr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:yandex-pro-taximeter" {...props}></Icon>
<style>
:global(.bpwg77ejr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.25 38.077a21.5 21.5 0 0 1-.005-28.149M7.74 38.077a21.5 21.5 0 0 0 .005-28.149M9.92 40.257a21.5 21.5 0 0 1 28.15-.005M9.92 7.748a21.5 21.5 0 0 0 28.15.005");
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
