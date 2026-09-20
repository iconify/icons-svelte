<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="kzztgab9v"/><path class="jhngf2nuw"/><path class="cwgmzl1jt"/><path class="q4ccz-ret"/><path class="kkw674b1a"/><path class="ywch90sba"/><path class="ilk2gccex"/><path class="v35i90uku"/><path class="k2ge1hzsr"/><path class="qqj79abfc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ski-lift-duotone-bold" {...props}></Icon>
<style>
:global(.cwgmzl1jt) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 12v3h4v-3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ilk2gccex) {
  d: path("M7 8v4");
}

:global(.jhngf2nuw) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 8v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k2ge1hzsr) {
  d: path("M15 15v4");
}

:global(.kkw674b1a) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 19v3h4v-3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kzztgab9v) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 4 16 16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.q4ccz-ret) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 15v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qqj79abfc) {
  d: path("M13 19v3h4v-3");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.v35i90uku) {
  d: path("M5 12v3h4v-3");
}

:global(.ywch90sba) {
  d: path("m3 4 16 16");
}

</style>
