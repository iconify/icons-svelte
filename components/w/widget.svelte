<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="asjz13yhu"/><rect class="k4wj3kzch"/><rect class="yib8en0bc"/><rect class="z5diw0-ju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:widget" {...props}></Icon>
<style>
:global(.asjz13yhu) {
  width: 16px;
  height: 16px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

:global(.k4wj3kzch) {
  width: 16px;
  height: 16px;
  x: 26.5px;
  y: 26.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

:global(.yib8en0bc) {
  width: 16px;
  height: 16px;
  x: 26.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

:global(.z5diw0-ju) {
  width: 16px;
  height: 16px;
  x: 5.5px;
  y: 26.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
