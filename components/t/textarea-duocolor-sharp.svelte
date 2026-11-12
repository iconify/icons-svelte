<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vgl54wu5w"/><path class="cbbods3vk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:textarea-duocolor-sharp" {...props}></Icon>
<style>
:global(.cbbods3vk) {
  d: path("M3 3h18v18H3Zm4 4h10M7 11h4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.vgl54wu5w) {
  stroke-opacity: 0.4;
  d: path("m12 18l6-6m-1 6l1-1");
}

</style>
