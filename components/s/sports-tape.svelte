<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iucs7l-9n"/><path class="k0w8urnyu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:sports-tape" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iucs7l-9n) {
  d: path("M2.5 11.5a8 8 0 1 0 16 0a8 8 0 1 0-16 0");
}

:global(.k0w8urnyu) {
  d: path("M10.5 19.5h11l-2-3h-2.75M7 11.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

</style>
