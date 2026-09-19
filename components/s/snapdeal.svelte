<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="az8alebap"/><path class="ad-js6b2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:snapdeal" {...props}></Icon>
<style>
:global(.ad-js6b2z) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.953 7.773l9.76 17.106H42.5L30.567 41.336H13.856L5.5 27.155z");
}

:global(.az8alebap) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.612 6.664H33.29l9.164 15.552l-10.577-.028l-3.84-6.517H20.92z");
}

</style>
