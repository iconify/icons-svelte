<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jdf5k2bjp"/><path class="dvho1cbbx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:tag-minus-duocolor-sharp" {...props}></Icon>
<style>
:global(.dvho1cbbx) {
  d: path("M9 3h6l4 4v14H5V7zm2 3h2");
}

:global(.jdf5k2bjp) {
  stroke-opacity: 0.4;
  d: path("M9 14h6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
