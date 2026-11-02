<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nqqqpab0e"/><path class="kra2j8bng"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:store-duocolor-sharp" {...props}></Icon>
<style>
:global(.kra2j8bng) {
  d: path("M3 3h18v6H3Zm2 6v12h14V9m-9 12v-6h4v6");
}

:global(.nqqqpab0e) {
  stroke-opacity: 0.4;
  d: path("M9 3v6m6-6v6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
