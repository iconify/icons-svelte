<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="igeivrb6g"/><path class="cpsj61b5w"/><path class="sygjc5bhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:xapk-install-buddy" {...props}></Icon>
<style>
:global(.cpsj61b5w) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.932 26.85v8a2.895 2.895 0 0 1-1.87 2.708L23.998 42.5l-13.062-4.942a2.895 2.895 0 0 1-1.87-2.708v-8m20.184-10.1l5.5-5.5");
}

:global(.igeivrb6g) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 26v16.5m0-37V15m14.932 5.35L42.5 25.5l-14.932 5.65L24 26zm0 0L33 18");
}

:global(.sygjc5bhw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.068 20.35L5.5 25.5l14.932 5.65L24 26Zm0 0L15 18m3.75-1.25l-5.5-5.5");
}

</style>
