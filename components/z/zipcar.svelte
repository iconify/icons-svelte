<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="b6yjgkcjy"/><path class="sk9mmr3wc"/><circle class="ypbzpacqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:zipcar" {...props}></Icon>
<style>
:global(.b6yjgkcjy) {
  cx: 24px;
  cy: 24px;
  r: 17.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.cpk0fnbgt) {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.sk9mmr3wc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.397 27.812h8.777m-2.345-1.784H18.538l9.022-11.346H12.857v2.925h7.446l-8.675 11.987h4.042m7.759 0h12.943m-12.265 0l2.58-3.566");
}

:global(.ypbzpacqu) {
  cx: 19.505px;
  cy: 30.918px;
  r: 2.401px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
