<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mwg9_qb3b"/><path class="iy2vliimq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:watch-duocolor-sharp" {...props}></Icon>
<style>
:global(.iy2vliimq) {
  d: path("M7 12a5 5 0 1 0 10 0a5 5 0 0 0-10 0m2-4V3h6v5m-6 8v5h6v-5");
}

:global(.mwg9_qb3b) {
  stroke-opacity: 0.4;
  d: path("M12 10v2h2");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
