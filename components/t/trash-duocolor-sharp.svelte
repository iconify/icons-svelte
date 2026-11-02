<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xjj5xybzs"/><path class="ao6tbsb4g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:trash-duocolor-sharp" {...props}></Icon>
<style>
:global(.ao6tbsb4g) {
  d: path("M6 6v15h12V6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.xjj5xybzs) {
  stroke-opacity: 0.4;
  d: path("M4 6h16M8 6V3h8v3");
}

</style>
