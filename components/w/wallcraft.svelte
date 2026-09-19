<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i4etjbheb"/><path class="gtqrm54cf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:wallcraft" {...props}></Icon>
<style>
:global(.gtqrm54cf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.5 16l-4.75 16L24 16l-4.75 16l-4.75-16");
}

:global(.i4etjbheb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.62 34.75L24 45.5L5.38 34.75v-21.5L24 2.5l18.62 10.75z");
}

</style>
