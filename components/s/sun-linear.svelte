<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="v90gbqbox"/><path class="lq7a-_8su"/><path class="pq5xj2bli"/><path class="qi4ad9bta"/><path class="i0kw3he6n"/><path class="de5cici1x"/><path class="f1qgw1bwi"/><path class="elckf4blp"/><path class="ftpy_bcfw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sun-linear" {...props}></Icon>
<style>
:global(.de5cici1x) {
  d: path("M19.0703 4.9292L18.6775 5.32204");
}

:global(.elckf4blp) {
  d: path("M19.0703 19.0708L18.6775 18.678");
}

:global(.f1qgw1bwi) {
  d: path("M5.32227 18.6782L4.92943 19.0711");
}

:global(.ftpy_bcfw) {
  d: path("M5.32227 5.32178L4.92943 4.92894");
}

:global(.i0kw3he6n) {
  d: path("M3 12L2 12");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lq7a-_8su) {
  d: path("M12 2V3");
}

:global(.pq5xj2bli) {
  d: path("M12 21V22");
}

:global(.qi4ad9bta) {
  d: path("M22 12L21 12");
}

:global(.v90gbqbox) {
  cx: 12px;
  cy: 12px;
  r: 6px;
}

</style>
