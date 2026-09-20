<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zqmma7y_j"/><path class="bt9yp9b-l"/><path class="cm7hgfbsm"/><path class="z5bq1khxp"/><path class="h5m00ybuy"/><path class="ap_bu5bso"/><path class="z5anc_e2t"/><path class="xj9o_6b5o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sync-two-way-duotone-thin" {...props}></Icon>
<style>
:global(.ap_bu5bso) {
  d: path("m15 6 3 3 -3 3");
}

:global(.bt9yp9b-l) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15 6 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cm7hgfbsm) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 15h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h5m00ybuy) {
  d: path("M4 9h14");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xj9o_6b5o) {
  d: path("m9 12 -3 3 3 3");
}

:global(.z5anc_e2t) {
  d: path("M6 15h14");
}

:global(.z5bq1khxp) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 12 -3 3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zqmma7y_j) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 9h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
