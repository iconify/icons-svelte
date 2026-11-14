<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q3wixnhae"/><path class="bv205xb1r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:rx-folder" {...props}></Icon>
<style>
:global(.bv205xb1r) {
  d: path("M9.75 11.25h4.5A1.75 1.75 0 0 1 16 13a1.75 1.75 0 0 1-1.75 1.75h-4.5A1.75 1.75 0 0 1 8 13a1.75 1.75 0 0 1 1.75-1.75m2.25 0v3.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q3wixnhae) {
  d: path("M3 7a2 2 0 0 1 2-2h4.5l2 2H19a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Z");
}

</style>
