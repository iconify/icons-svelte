<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="h60klubfx"/><ellipse class="feqemd3wq"/><ellipse class="nmt-hu03q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:teamward" {...props}></Icon>
<style>
:global(.feqemd3wq) {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 10.486px;
  ry: 6.955px;
}

:global(.h60klubfx) {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 19.5px;
  ry: 12.934px;
}

:global(.nmt-hu03q) {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.758px;
  ry: 6.955px;
}

</style>
