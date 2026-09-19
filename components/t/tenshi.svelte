<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ihhsgsb1n"/><path class="rmlps3biz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:tenshi" {...props}></Icon>
<style>
:global(.ihhsgsb1n) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 7.33h37M7.26 19.93h33.48M24 7.33c0 10.23.8 25.34-18.5 33.34");
}

:global(.rmlps3biz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 39.93c-8.54-2.47-16.79-12.8-19.2-20");
}

</style>
