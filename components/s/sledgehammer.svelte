<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qibdh8v3d"/><path class="p2sgvrbxt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:sledgehammer" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p2sgvrbxt) {
  d: path("M9.525 9.525za1.5 1.5 0 0 1 2.121 0l7.072 7.071a1.5 1.5 0 0 1 0 2.122a1.5 1.5 0 0 1-2.122 0l-7.071-7.072a1.5 1.5 0 0 1 0-2.121");
}

:global(.qibdh8v3d) {
  d: path("m2.896 7.669l4.773-4.773a2.625 2.625 0 0 1 3.712 0l.531.53a2.625 2.625 0 0 1 0 3.713l-4.773 4.773a2.625 2.625 0 0 1-3.713 0l-.53-.531a2.625 2.625 0 0 1 0-3.712");
}

</style>
