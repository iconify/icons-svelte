<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gtx4kfbor"/><path class="iqr3ry8kv"/><path class="o63zcjbok"/><path class="sryr5qb0a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:step-goal-duotone-thin" {...props}></Icon>
<style>
:global(.gtx4kfbor) {
  fill: currentColor;
  d: path("M3 19v-4h5l4 -4h4l4 4v4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iqr3ry8kv) {
  d: path("M3 19v-4h5l4 -4h4l4 4v4Z");
}

:global(.o63zcjbok) {
  d: path("M6 8V2");
}

:global(.sryr5qb0a) {
  d: path("M6 2h5v4H6");
}

</style>
