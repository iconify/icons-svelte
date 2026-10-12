<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="spsniib-y"/><rect class="rn313_sfk"/><rect class="s3k_glb0o"/><rect class="o2e188kpk"/><circle class="dgf_phh1j"/><path class="fy174ictx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:xylophone" {...props}></Icon>
<style>
:global(.dgf_phh1j) {
  cx: 19.75px;
  cy: 4.25px;
  r: 1.5px;
}

:global(.fy174ictx) {
  d: path("m18.4 3.6l-2.65-.85");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o2e188kpk) {
  width: 2.4px;
  height: 7px;
  x: 18.85px;
  y: 8.5px;
  rx: 0.75px;
}

:global(.rn313_sfk) {
  width: 2.4px;
  height: 13px;
  x: 8.15px;
  y: 5.5px;
  rx: 0.75px;
}

:global(.s3k_glb0o) {
  width: 2.4px;
  height: 10px;
  x: 13.55px;
  y: 7px;
  rx: 0.75px;
}

:global(.spsniib-y) {
  width: 2.4px;
  height: 16px;
  x: 2.75px;
  y: 4px;
  rx: 0.75px;
}

</style>
