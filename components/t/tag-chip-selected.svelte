<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ee7i0-fyn"/><path class="m5c3x7bui"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:tag-chip-selected" {...props}></Icon>
<style>
:global(.ee7i0-fyn) {
  d: path("M7.5 6.5h9A5.5 5.5 0 0 1 22 12a5.5 5.5 0 0 1-5.5 5.5h-9A5.5 5.5 0 0 1 2 12a5.5 5.5 0 0 1 5.5-5.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m5c3x7bui) {
  d: path("m5 12l1.75 1.75l2.75-3m3 1.25H18");
}

</style>
