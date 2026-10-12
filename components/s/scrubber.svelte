<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="sa0_z2bnn"/><path class="qmpxjhimp"/><circle class="ec0ebxb4q"/><path class="k1esgw06w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:scrubber" {...props}></Icon>
<style>
:global(.ec0ebxb4q) {
  cx: 10.25px;
  cy: 19.25px;
  r: 1.75px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k1esgw06w) {
  d: path("M12 19.25h9.25");
}

:global(.qmpxjhimp) {
  d: path("m11.02 6.8l2.46 1.4q.52.3 0 .6l-2.46 1.4q-.52.3-.52-.3V7.1q0-.6.52-.3M2.75 19.25H8.5");
}

:global(.sa0_z2bnn) {
  width: 18.5px;
  height: 11.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 2.5px;
}

</style>
