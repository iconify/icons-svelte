<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="c8wr58czu"/><path class="j2ngk5bzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:singpass" {...props}></Icon>
<style>
:global(.c8wr58czu) {
  cx: 24px;
  cy: 11.167px;
  r: 6.667px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.j2ngk5bzu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.402 43.5H17.598l2.264-23.265h8.276z");
}

</style>
