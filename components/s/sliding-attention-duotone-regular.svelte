<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pr37be5vj"/><path class="gzjf714fp"/><path class="wnbj5_30e"/><path class="cfrvezdaa"/><path class="b4x_isbqv"/><path class="d_6ujebpi"/><path class="x1_r36phd"/><path class="zy1jzxj5t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sliding-attention-duotone-regular" {...props}></Icon>
<style>
:global(.b4x_isbqv) {
  d: path("M8 6H5v12h3");
}

:global(.cfrvezdaa) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12.5 9.5 15 12l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.d_6ujebpi) {
  d: path("M16 6h3v12h-3");
}

:global(.gzjf714fp) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 6h3v12h-3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pr37be5vj) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 6H5v12h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wnbj5_30e) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x1_r36phd) {
  d: path("M9 12h6");
}

:global(.zy1jzxj5t) {
  d: path("M12.5 9.5 15 12l-2.5 2.5");
}

</style>
