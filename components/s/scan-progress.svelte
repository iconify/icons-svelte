<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mtqfx78sk"/><path class="obxv41bqt"/><path class="c969xj0nh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:scan-progress" {...props}></Icon>
<style>
:global(.c969xj0nh) {
  d: path("m7.5 9l4.5 2.5L16.5 9M12 11.5v6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mtqfx78sk) {
  d: path("M2.5 12a9.5 9.5 0 1 1 9.5 9.5");
}

:global(.obxv41bqt) {
  d: path("M12 6.5L16.5 9v6L12 17.5L7.5 15V9Z");
}

</style>
