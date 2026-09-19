<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="syza-eb1b"/><rect class="r37ei0b7r"/><rect class="ta_9273lc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:statsfm-spotistats" {...props}></Icon>
<style>
:global(.r37ei0b7r) {
  width: 11.84px;
  height: 15.893px;
  x: 29.92px;
  y: 26.607px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

:global(.syza-eb1b) {
  width: 11.84px;
  height: 37px;
  x: 18.08px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

:global(.ta_9273lc) {
  width: 11.84px;
  height: 28.148px;
  x: 6.24px;
  y: 14.352px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

</style>
