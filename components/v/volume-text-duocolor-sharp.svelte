<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c86uuzbhr"/><path class="kjo_8vpbd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:volume-text-duocolor-sharp" {...props}></Icon>
<style>
:global(.c86uuzbhr) {
  stroke-opacity: 0.4;
  d: path("M3 9h6M6 9v6");
}

:global(.kjo_8vpbd) {
  d: path("M13 10h3l5-5v14l-5-5h-3z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
