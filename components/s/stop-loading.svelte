<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a88uu03mv"/><path class="g_9gv8lnn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:stop-loading" {...props}></Icon>
<style>
:global(.a88uu03mv) {
  d: path("M12 2.5A9.5 9.5 0 1 1 2.5 12");
}

:global(.g_9gv8lnn) {
  fill: currentColor;
  d: path("M11 9.25h2A1.75 1.75 0 0 1 14.75 11v2A1.75 1.75 0 0 1 13 14.75h-2A1.75 1.75 0 0 1 9.25 13v-2A1.75 1.75 0 0 1 11 9.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
