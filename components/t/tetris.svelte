<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x0u_g9b9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:tetris" {...props}></Icon>
<style>
:global(.x0u_g9b9m) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 37V24h13v13zm13 0V24h13v13zm0-13V11h13v13zm13 13V24h13v13z");
}

</style>
