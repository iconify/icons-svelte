<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xb1ky5bec"/><path class="wqu0yvyoz"/><path class="zvuby9blz"/><path class="v5srdkbdr"/><path class="sqsrstbfr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:warm-pool-outline-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sqsrstbfr) {
  d: path("M16 3v3.5");
}

:global(.v5srdkbdr) {
  d: path("M12 2v3.5");
}

:global(.wqu0yvyoz) {
  d: path("M13 12a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

:global(.xb1ky5bec) {
  d: path("M2 12a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.zvuby9blz) {
  d: path("M8 3v3.5");
}

</style>
