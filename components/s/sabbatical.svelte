<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rsh-9mbyd"/><path class="vh5jvzb1s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:sabbatical" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rsh-9mbyd) {
  d: path("M5.5 21.5V13a6.5 5 0 0 1 13 0v8.5Z");
}

:global(.vh5jvzb1s) {
  d: path("M7 4h10a2 2 0 0 1 2 2a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2a2 2 0 0 1 2-2m3.25 11h3.5a1.75 1.75 0 0 1 1.75 1.75V17a1.75 1.75 0 0 1-1.75 1.75h-3.5A1.75 1.75 0 0 1 8.5 17v-.25A1.75 1.75 0 0 1 10.25 15M5.5 12.5c-2.5.25-3 2.5-3 4.5v2.5c0 1.25 1 2 3 2m13-9c2.5.25 3 2.5 3 4.5v2.5c0 1.25-1 2-3 2M9 4v4m6-4v4");
}

</style>
