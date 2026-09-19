<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s-lgpdkzf"/><circle class="agwfqdcrf"/><circle class="xm5dg2ibm"/><circle class="ho0e36b0w"/><path class="p_9h7mi-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:share-via-http" {...props}></Icon>
<style>
:global(.agwfqdcrf) {
  cx: 14px;
  cy: 22.956px;
  r: 3.925px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ho0e36b0w) {
  cx: 24px;
  cy: 35.956px;
  r: 3.925px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.p_9h7mi-c) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.608 26.066l-5.216 6.781m-10-6.781l5.216 6.781");
}

:global(.s-lgpdkzf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.344 16.81a6.1 6.1 0 0 0-2.35.468a10.745 10.745 0 0 0-20.274-3.146a7.706 7.706 0 1 0-2.511 14.99h25.135a6.156 6.156 0 1 0 0-12.312");
}

:global(.xm5dg2ibm) {
  cx: 34px;
  cy: 22.956px;
  r: 3.925px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
