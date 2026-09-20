<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zhy5nnbig"/><path class="mm5qhtb0x"/><path class="o_ssmh9ez"/><path class="h2-2dgnfu"/><path class="fb4zxqney"/><path class="ln075ccaf"/><path class="cjzdtdb-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:time-zone-map-duotone-regular" {...props}></Icon>
<style>
:global(.cjzdtdb-a) {
  d: path("M16 15h2.5");
}

:global(.fb4zxqney) {
  d: path("M12 15a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.h2-2dgnfu) {
  d: path("M12 3v18");
}

:global(.ln075ccaf) {
  d: path("M16 12v3");
}

:global(.mm5qhtb0x) {
  fill: currentColor;
  d: path("M12 15a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o_ssmh9ez) {
  d: path("M3 12a9 9 0 1 0 18 0 9 9 0 1 0 -18 0");
}

:global(.zhy5nnbig) {
  fill: currentColor;
  d: path("M3 12a9 9 0 1 0 18 0 9 9 0 1 0 -18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
