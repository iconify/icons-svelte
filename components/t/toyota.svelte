<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="ig6bpsbwo"/><ellipse class="tboscobjx"/><path class="ckhgq0c9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:toyota" {...props}></Icon>
<style>
:global(.ckhgq0c9z) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.98 13.802c1.652 1.071 2.533 2.324 2.533 3.604h0c0 3.635-6.946 6.581-15.513 6.581h0c-8.568 0-15.513-2.946-15.513-6.58h0c0-1.284.883-2.538 2.542-3.611");
}

:global(.ig6bpsbwo) {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 20.5px;
  ry: 13.175px;
}

:global(.tboscobjx) {
  cx: 24px;
  cy: 24.872px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.958px;
  ry: 12.303px;
}

</style>
