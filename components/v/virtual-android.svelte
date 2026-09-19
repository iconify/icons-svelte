<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c69remmqt"/><path class="krm24bbbf"/><path class="j0tgnibig"/><path class="e1i70gb0l"/><path class="yja8sjnfb"/><path class="itb322wcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:virtual-android" {...props}></Icon>
<style>
:global(.c69remmqt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 3.5l17.754 10.25v20.5L24 44.5L6.246 34.25v-20.5z");
}

:global(.e1i70gb0l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 8.625l-8.877 5.125L24 18.875l8.877-5.125zM10.685 31.687l2.958-1.708m5.919 3.417l-5.919-3.417v-6.835");
}

:global(.itb322wcx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.439 33.396l5.918-3.417v-6.835");
}

:global(.j0tgnibig) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.082 15.459L24 12.042l5.918 3.417");
}

:global(.krm24bbbf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.754 13.75L24 24L6.246 13.75M24 24v20.5m0-35.875v3.417");
}

:global(.yja8sjnfb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.562 26.563v10.25l-8.877-5.125v-10.25zm8.877 0v10.25l8.876-5.125v-10.25zm8.877 5.124l-2.96-1.708");
}

</style>
