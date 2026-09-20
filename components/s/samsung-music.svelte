<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="e_81gsb2o"/><path class="bvfugvi_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:samsung-music" {...props}></Icon>
<style>
:global(.bvfugvi_t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.559 35.481V4.88h4.358a13.32 13.32 0 0 1 13.321 13.322v5.542");
}

:global(.e_81gsb2o) {
  cx: 15.16px;
  cy: 35.481px;
  r: 8.399px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
