<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c1g0k8fft"/><path class="wnbj5_30e"/><path class="lk97rhbbb"/><path class="ekfvrj1wr"/><path class="ythi7dbly"/><path class="yngda3bvc"/><path class="x1_r36phd"/><path class="rrzohjbez"/><path class="gstzuxb9r"/><path class="wggowmhtc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:rowing-machine-duotone-regular" {...props}></Icon>
<style>
:global(.c1g0k8fft) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 15h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ekfvrj1wr) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 7v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gstzuxb9r) {
  d: path("M5 7v4");
}

:global(.lk97rhbbb) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 12v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rrzohjbez) {
  d: path("M12 12v3");
}

:global(.wggowmhtc) {
  d: path("M5 9h4");
}

:global(.wnbj5_30e) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x1_r36phd) {
  d: path("M9 12h6");
}

:global(.yngda3bvc) {
  d: path("M3 15h18");
}

:global(.ythi7dbly) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 9h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
