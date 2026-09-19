<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nu9609c3e"/><circle class="r-0b752he"/><circle class="amygq3bmr"/><circle class="ljrdu4bod"/><circle class="r00k-obua"/><circle class="zf_716b0m"/><path class="irag0hb0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:that-shopping-list" {...props}></Icon>
<style>
:global(.amygq3bmr) {
  cx: 24.032px;
  cy: 26.096px;
  r: 3.906px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.irag0hb0c) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.557 25.143l-2.001 2.001q-.142.142-.286 0l-.953-.953");
}

:global(.ljrdu4bod) {
  cx: 34.512px;
  cy: 26.096px;
  r: 3.906px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.nu9609c3e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.61 19.999h-7.527l-7.43-12.386c-.382-.571-.954-.953-1.716-.953s-1.334.382-1.715.953L14.792 20H7.454c-2 0-3.334 1.905-2.858 3.715L8.789 39.34c.286 1.143 1.429 2 2.572 2H36.61a2.66 2.66 0 0 0 2.572-2l4.192-15.53c.572-1.905-.858-3.81-2.763-3.81Zm-16.578-7.622l4.573 7.622h-9.05zm-9.05 7.622h18.101");
}

:global(.r-0b752he) {
  cx: 13.552px;
  cy: 26.096px;
  r: 3.906px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.r00k-obua) {
  cx: 30.035px;
  cy: 35.623px;
  r: 3.906px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.zf_716b0m) {
  cx: 18.316px;
  cy: 35.623px;
  r: 3.906px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
