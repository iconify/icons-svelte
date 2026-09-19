<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y6zfn5srp"/><path class="iw2vl3z_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:zenkit" {...props}></Icon>
<style>
:global(.iw2vl3z_p) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.5L17.632 24L24 43.5L30.368 24ZM9 24h30");
}

:global(.y6zfn5srp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.5L9 24l15 19.5L39 24z");
}

</style>
