<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hnvnn0bgl"/><path class="s0exaccue"/><path class="b71b74nge"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:shield-sync" {...props}></Icon>
<style>
:global(.b71b74nge) {
  d: path("M10.75 6.75L12 8l-1.25 1.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hnvnn0bgl) {
  d: path("m12 2.75l7.5 2.75v6c0 4.7-3.1 8-7.5 9.75c-4.4-1.75-7.5-5.05-7.5-9.75v-6Z");
}

:global(.s0exaccue) {
  d: path("M15.5 11.5A3.5 3.5 0 1 1 12 8");
}

</style>
