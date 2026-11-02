<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n52tb9b6r"/><path class="bg2ejdbaq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:zodiac-aries-duocolor-sharp" {...props}></Icon>
<style>
:global(.bg2ejdbaq) {
  d: path("M12 5v16");
}

:global(.n52tb9b6r) {
  stroke-opacity: 0.4;
  d: path("M12 5a5 5 0 1 0-4 8m4-8a5 5 0 1 1 4 8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
