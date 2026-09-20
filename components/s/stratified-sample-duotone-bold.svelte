<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yeodwlnkh"/><path class="fcpcpjxqg"/><path class="vcjsoxbsd"/><path class="aqn8oeb4o"/><path class="g55pkgb9q"/><path class="h2sq3fbpa"/><path class="mg7aqnbsf"/><path class="o04kmobcg"/><path class="d8abqfbpc"/><path class="heav9sszs"/><path class="xyj-l9cjp"/><path class="bc072wkjn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:stratified-sample-duotone-bold" {...props}></Icon>
<style>
:global(.aqn8oeb4o) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 4h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.bc072wkjn) {
  d: path("M16 21a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.d8abqfbpc) {
  d: path("M3 11h18");
}

:global(.fcpcpjxqg) {
  fill: currentColor;
  d: path("M11 14.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.g55pkgb9q) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 11h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h2sq3fbpa) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.heav9sszs) {
  d: path("M11 14.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.mg7aqnbsf) {
  d: path("M3 4h18");
}

:global(.o04kmobcg) {
  d: path("M6 7.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vcjsoxbsd) {
  fill: currentColor;
  d: path("M16 21a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.xyj-l9cjp) {
  d: path("M3 18h18");
}

:global(.yeodwlnkh) {
  fill: currentColor;
  d: path("M6 7.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
