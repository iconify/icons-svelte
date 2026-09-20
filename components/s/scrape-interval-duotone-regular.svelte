<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pd-i35blz"/><path class="iulb4mb6k"/><path class="k_7z1bcnp"/><path class="irk9zbcmx"/><path class="c39r_abdo"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="f26bn-hui"/><path class="l517yxbln"/><path class="dti01qb8s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:scrape-interval-duotone-regular" {...props}></Icon>
<style>
:global(.c39r_abdo) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dti01qb8s) {
  d: path("M16 9v6");
}

:global(.f26bn-hui) {
  d: path("M8 9v6");
}

:global(.irk9zbcmx) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.iulb4mb6k) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k_7z1bcnp) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l517yxbln) {
  d: path("M12 9v6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.pd-i35blz) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

</style>
