<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="rknchmb5r"/><path class="kf_mvwa8r"/><circle class="k-pua8b2l"/><path class="b3ocf71ya"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:user-medal" {...props}></Icon>
<style>
:global(.b3ocf71ya) {
  d: path("m17 11.75l-.75 3l2-1l2 1l-.75-3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k-pua8b2l) {
  cx: 18.25px;
  cy: 9.25px;
  r: 2.5px;
}

:global(.kf_mvwa8r) {
  d: path("M4 20.25h11a.75.75 0 0 0 .75-.75c0-3-2.8-5.25-6.25-5.25S3.25 16.5 3.25 19.5a.75.75 0 0 0 .75.75");
}

:global(.rknchmb5r) {
  cx: 9.5px;
  cy: 7.75px;
  r: 3.75px;
}

</style>
