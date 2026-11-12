<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r5pfwdbos"/><path class="zneykhbxf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:security-key-duocolor-sharp" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.r5pfwdbos) {
  stroke-opacity: 0.4;
  d: path("M15 9h6v6h-6");
}

:global(.zneykhbxf) {
  d: path("M3 7h12v10H3Zm6 4v2m12-1h-2");
}

</style>
