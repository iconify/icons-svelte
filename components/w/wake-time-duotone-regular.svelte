<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q82tmjh1i"/><path class="orxbb2h0a"/><path class="m1pvpub-n"/><path class="a5tuk3h7e"/><path class="zkgvk4bog"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:wake-time-duotone-regular" {...props}></Icon>
<style>
:global(.a5tuk3h7e) {
  d: path("M4 10h16");
}

:global(.m1pvpub-n) {
  d: path("M7 10a5 5 0 0 1 10 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.orxbb2h0a) {
  d: path("M3 20a3 3 0 0 1 0 -6h18a3 3 0 0 1 0 6Z");
}

:global(.q82tmjh1i) {
  fill: currentColor;
  d: path("M3 20a3 3 0 0 1 0 -6h18a3 3 0 0 1 0 6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.zkgvk4bog) {
  d: path("M12 2v3");
}

</style>
