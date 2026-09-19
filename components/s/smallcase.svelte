<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="thjl7gbdb"/><path class="e67hdqbuu"/><ellipse transform="rotate(-52.425 35.236 29.132)" class="psf18xbos"/><path class="z42ekbcmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:smallcase" {...props}></Icon>
<style>
:global(.e67hdqbuu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.165 24v19.5l16.882-9.75v-19.5m-16.882-4.026l6.97 4.026l-6.97 4.026l-6.97-4.026z");
}

:global(.psf18xbos) {
  cx: 35.236px;
  cy: 29.132px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.301px;
  ry: 3.138px;
}

:global(.thjl7gbdb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.165 4.5l16.882 9.75L26.165 24L9.283 14.25z");
}

:global(.z42ekbcmo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.528 24.753l-4.55 5.212l9.1 5.337z");
}

</style>
