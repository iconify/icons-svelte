<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rithh5b-z"/><path class="h4f8xqbrj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:speaker-duocolor-sharp" {...props}></Icon>
<style>
:global(.h4f8xqbrj) {
  d: path("M5 3h14v18H5Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rithh5b-z) {
  stroke-opacity: 0.4;
  d: path("M12 7h.01M9 14a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

</style>
