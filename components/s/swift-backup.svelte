<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yf0sgtiyb"/><path class="j4s1ueoeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:swift-backup" {...props}></Icon>
<style>
:global(.j4s1ueoeq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.444 25.179v7.481L24 42.5m16.444-37v7.481L30.251 19.08M7.556 5.5h32.888");
}

:global(.yf0sgtiyb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.444 25.179L7.556 5.5m27.792 30.21L7.556 19.08v13.58L24 42.5");
}

</style>
