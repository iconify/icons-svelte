<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="yn6j5ab9x"/><path class="fze1ck2oy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:unread-line-duotone" {...props}></Icon>
<style>
:global(.fze1ck2oy) {
  d: path("M10.1426 16.5L17.9997 7.5");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yn6j5ab9x) {
  stroke-linejoin: round;
  d: path("M7 12.9L10.1429 16.5L18 7.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
