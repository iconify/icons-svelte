<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sp4f4x76l"/><path class="m2qdb_b7x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:tent-duocolor-sharp" {...props}></Icon>
<style>
:global(.m2qdb_b7x) {
  d: path("M14 3L5 21m5-18l9 18M3 21h18");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sp4f4x76l) {
  stroke-opacity: 0.4;
  d: path("m10 21l2-5l2 5");
}

</style>
