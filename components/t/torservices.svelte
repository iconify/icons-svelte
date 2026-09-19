<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qkp3zubwt"/><path class="mu5fntbqw"/><path class="rbo38fmwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:torservices" {...props}></Icon>
<style>
:global(.mu5fntbqw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.985 24a14.985 14.985 0 1 0-4.39 10.596");
}

:global(.qkp3zubwt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.797 39.203A21.5 21.5 0 1 0 24 2.5m-6.06.866A21.512 21.512 0 0 0 5.589 35.109");
}

:global(.rbo38fmwq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.53 24A8.47 8.47 0 1 0 24 15.53");
}

</style>
