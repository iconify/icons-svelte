<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rtlx-6oiu"/><path class="lc6184j1d"/><path class="kcnga8bli"/><path class="yy0mqcc-b"/><path class="pga6n1bci"/><path class="bgz3owcvd"/><path class="vux4gkbhn"/><path class="nj9g-accq"/><path class="axyqg5uel"/><path class="jkuojibnm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:stacked-bar-duotone-regular" {...props}></Icon>
<style>
:global(.axyqg5uel) {
  d: path("M16 14v6");
}

:global(.bgz3owcvd) {
  d: path("M8 4v7");
}

:global(.jkuojibnm) {
  d: path("M3 20h18");
}

:global(.kcnga8bli) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 8v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lc6184j1d) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 14v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nj9g-accq) {
  d: path("M16 8v3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pga6n1bci) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rtlx-6oiu) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 4v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vux4gkbhn) {
  d: path("M8 14v6");
}

:global(.yy0mqcc-b) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 14v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
