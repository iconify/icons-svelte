<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="v4leetqra"/><path class="imesovs4v"/><circle transform="rotate(-89.236 34.38 11.974)" class="q4egjbb0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:tagspaces" {...props}></Icon>
<style>
:global(.imesovs4v) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.433 34.277l3.46-3.46l4.886 4.885l-3.46 3.46zm3.332-7.996l3.46-3.46l7.217 7.216l-3.46 3.46zm2.394-8.935l3.46-3.46l10.487 10.487l-3.46 3.46z");
}

:global(.q4egjbb0w) {
  cx: 34.38px;
  cy: 11.974px;
  r: 3.119px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.v4leetqra) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.769 5.585L5.5 26.85l15.565 15.565L42.5 20.98V5.584Z");
}

</style>
