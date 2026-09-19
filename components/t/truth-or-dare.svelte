<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="dxuuasb_r"/><path class="f2_udfbxc"/><circle class="et8xzacsh"/><path class="td8vq2ose"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:truth-or-dare" {...props}></Icon>
<style>
:global(.cpk0fnbgt) {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.dxuuasb_r) {
  cx: 14.225px;
  cy: 28.035px;
  r: 0.75px;
  fill: currentColor;
}

:global(.et8xzacsh) {
  cx: 34.18px;
  cy: 19.029px;
  r: 0.75px;
  fill: currentColor;
}

:global(.f2_udfbxc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m15.815 11.831l-1.253 12.051");
}

:global(.td8vq2ose) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.651 30.777c-.128 1.23-.742 2.344-1.632 3.15s-2.056 1.306-3.287 1.306c-2.461 0-4.249-1.995-3.993-4.456c.128-1.23.67-2.438 1.633-3.151c1-.74 3.37-1.952 3.566-3.837M18.624 44.822L29.376 3.178");
}

</style>
