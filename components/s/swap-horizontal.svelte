<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="seqyflbij"/><path class="abwhqy5wb"/><path class="ok9gfabge"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:swap-horizontal" {...props}></Icon>
<style>
:global(.abwhqy5wb) {
  d: path("M16.5 4.5L20 8l-3.5 3.5m3.5 9V16H4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ok9gfabge) {
  d: path("M7.5 12.5L4 16l3.5 3.5");
}

:global(.seqyflbij) {
  d: path("M4 3.5V8h16");
}

</style>
