<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="x7zto92vq"/><rect class="kqkiv7bzq"/><rect class="kdo6u4bhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:spotistats" {...props}></Icon>
<style>
:global(.kdo6u4bhv) {
  width: 7.68px;
  height: 24.721px;
  x: 6.5px;
  y: 16.572px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.327px;
}

:global(.kqkiv7bzq) {
  width: 7.68px;
  height: 15.244px;
  x: 33.821px;
  y: 26.049px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.327px;
}

:global(.x7zto92vq) {
  width: 7.68px;
  height: 34.586px;
  x: 20.16px;
  y: 6.707px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.327px;
}

</style>
