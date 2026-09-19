<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="p3-37f6cr"/><circle class="fkbkg5oka"/><path class="kdpzf30wi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:sober-time" {...props}></Icon>
<style>
:global(.fkbkg5oka) {
  cx: 24px;
  cy: 29.167px;
  r: 1px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.kdpzf30wi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 8.5l17.898 31H6.102zm0 12.833v6.834m.707 1.707l2.946 2.946");
}

:global(.p3-37f6cr) {
  cx: 24px;
  cy: 29.167px;
  r: 10.333px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
