<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q_jvd8nnh"/><path class="e5ocjco1b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:trophy-big-ears" {...props}></Icon>
<style>
:global(.e5ocjco1b) {
  d: path("M8 4.5c-5.5 0-5.5 7.5.5 5.5M16 4.5c5.5 0 5.5 7.5-.5 5.5M12 12v5m-3 0h6l1 4H8Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q_jvd8nnh) {
  d: path("M8 3h8v5a4 4 0 0 1-8 0Z");
}

</style>
