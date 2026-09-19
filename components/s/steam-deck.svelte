<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="ui1zimbxa"/><path class="arrnj340j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:steam-deck" {...props}></Icon>
<style>
:global(.arrnj340j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 13.5v-11a21.5 21.5 0 0 0 0 43v-11");
}

:global(.ui1zimbxa) {
  cx: 24px;
  cy: 24px;
  r: 10.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
