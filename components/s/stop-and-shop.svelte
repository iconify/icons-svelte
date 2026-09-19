<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="r975nsb7x"/><circle class="gmvelmxic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:stop-and-shop" {...props}></Icon>
<style>
:global(.gmvelmxic) {
  cx: 24px;
  cy: 35.182px;
  r: 9.318px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.r975nsb7x) {
  cx: 24px;
  cy: 12.818px;
  r: 9.318px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
