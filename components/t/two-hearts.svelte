<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ywimfdf7z"/><path class="rvr4ym94x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:two-hearts" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rvr4ym94x) {
  d: path("M15.84 18.05c-.25 0-.5-.09-.68-.25c-2.05-1.7-4.74-3.87-4.74-6.78c0-1.68 1.27-3.04 2.88-3.04c.99 0 1.86.5 2.54 1.36c.68-.86 1.55-1.36 2.54-1.36c1.61 0 2.88 1.36 2.88 3.04c0 2.91-2.7 5.08-4.74 6.79c-.19.15-.43.25-.68.25Z");
}

:global(.ywimfdf7z) {
  d: path("M8.19 16.05c-.25 0-.5-.09-.68-.25c-2.05-1.7-4.74-3.87-4.74-6.78c0-1.68 1.27-3.04 2.88-3.04c.99 0 1.86.5 2.54 1.36c.68-.86 1.55-1.36 2.54-1.36c1.61 0 2.88 1.36 2.88 3.04c0 2.91-2.7 5.08-4.74 6.79c-.19.15-.43.25-.68.25Z");
}

</style>
