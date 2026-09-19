<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="wp35qerjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:tab" {...props}></Icon>
<style>
:global(.j3s9ivbxi) {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

:global(.wp35qerjq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.018 24.925h8.33m-13.683.802l5.89-5.89m3.628 17.659V24.925m9.753 9.428a3.143 3.143 0 0 1-3.143 3.143h0a3.143 3.143 0 0 1-3.144-3.143V32.31a3.143 3.143 0 0 1 3.144-3.142h0a3.143 3.143 0 0 1 3.143 3.142m0 5.186v-8.328m3.277 3.143a3.143 3.143 0 0 1 3.143-3.143h0a3.143 3.143 0 0 1 3.144 3.143v2.043a3.143 3.143 0 0 1-3.144 3.142h0a3.143 3.143 0 0 1-3.143-3.142m0 3.142V24.925");
}

</style>
