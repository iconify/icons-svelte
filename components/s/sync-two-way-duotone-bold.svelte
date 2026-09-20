<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nqkir3lvj"/><path class="c48smxb5m"/><path class="mqx1fpbzs"/><path class="r8p1fm0mz"/><path class="h5m00ybuy"/><path class="ap_bu5bso"/><path class="z5anc_e2t"/><path class="xj9o_6b5o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sync-two-way-duotone-bold" {...props}></Icon>
<style>
:global(.ap_bu5bso) {
  d: path("m15 6 3 3 -3 3");
}

:global(.c48smxb5m) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 6 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h5m00ybuy) {
  d: path("M4 9h14");
}

:global(.mqx1fpbzs) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 15h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nqkir3lvj) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 9h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r8p1fm0mz) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 12 -3 3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.xj9o_6b5o) {
  d: path("m9 12 -3 3 3 3");
}

:global(.z5anc_e2t) {
  d: path("M6 15h14");
}

</style>
