<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nte11tb2t"/><path class="wqs6zb7fx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:surdo-help" {...props}></Icon>
<style>
:global(.nte11tb2t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 5.5v9.25m0 18.5v9.25h-37v-37h37");
}

:global(.wqs6zb7fx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.25 32.75v-17.5h17.5v17.5");
}

</style>
