<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qs4cszaei"/><path class="yrtd6kb7a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:umbrella-rain" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qs4cszaei) {
  d: path("M3.5 15.5a8.5 8.5 0 0 1 17 0q-2.75-1.75-5.75 0q-2.75-1.75-5.5 0q-3-1.75-5.75 0");
}

:global(.yrtd6kb7a) {
  d: path("M12 14.75v4.75a1.75 1.75 0 0 1-3.5 0M6 2.5L5.25 5m7.25-2.5L12 4.25m6.75-1.75L18 5");
}

</style>
