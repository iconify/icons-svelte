<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h5m00ybuy"/><path class="ap_bu5bso"/><path class="z5anc_e2t"/><path class="xj9o_6b5o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sync-two-way-outline-thin" {...props}></Icon>
<style>
:global(.ap_bu5bso) {
  d: path("m15 6 3 3 -3 3");
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

</style>
