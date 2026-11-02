<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kumogieiq"/><path class="md225ib-y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shuffle-duocolor-round" {...props}></Icon>
<style>
:global(.kumogieiq) {
  stroke-opacity: 0.4;
  d: path("m3 3l6 6m6 12h6v-6m0 6l-6-6");
}

:global(.md225ib-y) {
  d: path("M15 3h6v6m0-6L3 21");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
