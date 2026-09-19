<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yzc_yr5vq"/><path class="wvxip_pcu"/><path class="sf7mf6s8w"/><path class="jz-ap8b3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:zee5" {...props}></Icon>
<style>
:global(.jz-ap8b3m) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.405 45.5a21.502 21.502 0 0 1 .277-43");
}

:global(.sf7mf6s8w) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.637 40.992a17.935 17.935 0 1 1 1.55-32.417");
}

:global(.wvxip_pcu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.951 36.955A13.189 13.189 0 0 1 25.642 11.2");
}

:global(.yzc_yr5vq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.291 27.547h3.667m-3.667-7.334h3.667m-3.667 3.667h2.383m-2.383-3.667v7.334m8.112-.143h3.667m-3.667-7.335h3.667m-3.667 3.667h2.383m-2.383-3.667v7.335m-16.575-7.388h4.859l-4.859 7.334h4.859m19.146-.485a2.88 2.88 0 0 0 2.2.642h.275a2.427 2.427 0 0 0 2.384-2.384h0a2.427 2.427 0 0 0-2.384-2.384h-2.475v-2.567h4.86");
}

</style>
