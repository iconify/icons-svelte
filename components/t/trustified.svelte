<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="or409g7ug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:trustified" {...props}></Icon>
<style>
:global(.cpk0fnbgt) {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.or409g7ug) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m8.477 20.746l8.166 12.974l22.88-19.44l-23.046 11.275z");
}

</style>
