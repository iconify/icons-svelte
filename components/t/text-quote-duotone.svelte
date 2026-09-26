<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p3f9wkane"/><path class="ljyyucbks"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:text-quote-duotone" {...props}></Icon>
<style>
:global(.ljyyucbks) {
  d: path("M3 12V19");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p3f9wkane) {
  stroke-opacity: 0.4;
  d: path("M3 5H16M7 12H21M7 19H21");
}

</style>
