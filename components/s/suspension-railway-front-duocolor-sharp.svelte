<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jyr9_ub8c"/><path class="qp8c_vbrx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:suspension-railway-front-duocolor-sharp" {...props}></Icon>
<style>
:global(.jyr9_ub8c) {
  stroke-opacity: 0.4;
  d: path("M3 4h18M9 4v5m6-5v5m-6 8h.01M15 17h.01");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qp8c_vbrx) {
  d: path("M5 9h14v11H5zm0 5h14");
}

</style>
