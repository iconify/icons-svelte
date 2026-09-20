<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kt4kzrb6r"/><path class="nvn647bwx"/><path class="p7tekpb9x"/><path class="tea8p3bbk"/><path class="ennto9b9x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sunlight-break-outline-regular" {...props}></Icon>
<style>
:global(.ennto9b9x) {
  d: path("M16 16h5");
}

:global(.kt4kzrb6r) {
  d: path("M5 21V4h8v17");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nvn647bwx) {
  d: path("M10 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.p7tekpb9x) {
  d: path("M16 8h5");
}

:global(.tea8p3bbk) {
  d: path("M16 12h5");
}

</style>
