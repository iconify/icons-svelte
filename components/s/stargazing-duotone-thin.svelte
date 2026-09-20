<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z9do-djry"/><path class="i_lu0jbgc"/><path class="l1_xhdcdr"/><path class="k-tnn71bj"/><path class="phi687keh"/><path class="znfuzdoyp"/><path class="mt0duqbnk"/><path class="luzoskb2e"/><path class="l1lmw_bdv"/><path class="saj3disjq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:stargazing-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i_lu0jbgc) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k-tnn71bj) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 11h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l1_xhdcdr) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 8v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l1lmw_bdv) {
  d: path("M13 11h6");
}

:global(.luzoskb2e) {
  d: path("M16 8v6");
}

:global(.mt0duqbnk) {
  d: path("M4 6h6");
}

:global(.phi687keh) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 20c4 -3 14 -3 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.saj3disjq) {
  d: path("M3 20c4 -3 14 -3 18 0");
}

:global(.z9do-djry) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 3v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.znfuzdoyp) {
  d: path("M7 3v6");
}

</style>
