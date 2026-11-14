<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c9lv6zbld"/><path class="i8ljbwbci"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:youth-academy" {...props}></Icon>
<style>
:global(.c9lv6zbld) {
  d: path("M11.618 20.5H3v-10l7.5-7l7.5 7v.482");
}

:global(.i8ljbwbci) {
  d: path("M11.6 20.5H8.5v-6h4v4.1m3.5-2.85a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-1.75 6c0-1.75 1.75-3 3.75-3s3.75 1.25 3.75 3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
