<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ulztkdbrc"/><path class="igy0zughn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:simplelauncher" {...props}></Icon>
<style>
:global(.igy0zughn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 23.699L24 8.781l18.5 14.918");
}

:global(.ulztkdbrc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.868 14.75v24.47h8.952v-8.953h8.356v8.952h8.952V19.526");
}

</style>
