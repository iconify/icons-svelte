<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ygr-3532s"/><path class="ic32ko01d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:warehouse-duocolor-sharp" {...props}></Icon>
<style>
:global(.ic32ko01d) {
  d: path("M3 21h18M5 21V10l6-3h2l6 3v11");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ygr-3532s) {
  stroke-opacity: 0.4;
  d: path("M9 21v-8h6v8m-6-4h6");
}

</style>
