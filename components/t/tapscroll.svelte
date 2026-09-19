<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a4pzx531d"/><path class="g--_r3bkd"/><path class="r489lq6np"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:tapscroll" {...props}></Icon>
<style>
:global(.a4pzx531d) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 24c0 11.874-9.626 21.5-21.5 21.5h0C12.126 45.5 2.5 35.874 2.5 24q0 0 0 0C2.5 12.126 12.126 2.5 24 2.5h0c11.874 0 21.5 9.626 21.5 21.5");
}

:global(.g--_r3bkd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.263 24.9l-11.9-12.07l-11.9 12.07");
}

:global(.r489lq6np) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.263 34.136l-11.9-12.07l-11.9 12.07");
}

</style>
