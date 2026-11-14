<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b7-xbqjtq"/><path class="dl-6y4b8e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:shofar" {...props}></Icon>
<style>
:global(.b7-xbqjtq) {
  d: path("M11.5 5c0 6-1.5 11-7.5 13.5l.5 2.25C14 19.5 20.5 13 20.5 5");
}

:global(.dl-6y4b8e) {
  d: path("M11.5 5a4.5 1.75 0 1 0 9 0a4.5 1.75 0 1 0-9 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
