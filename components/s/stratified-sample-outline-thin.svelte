<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mg7aqnbsf"/><path class="o04kmobcg"/><path class="d8abqfbpc"/><path class="heav9sszs"/><path class="xyj-l9cjp"/><path class="bc072wkjn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:stratified-sample-outline-thin" {...props}></Icon>
<style>
:global(.bc072wkjn) {
  d: path("M16 21a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.d8abqfbpc) {
  d: path("M3 11h18");
}

:global(.heav9sszs) {
  d: path("M11 14.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mg7aqnbsf) {
  d: path("M3 4h18");
}

:global(.o04kmobcg) {
  d: path("M6 7.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.xyj-l9cjp) {
  d: path("M3 18h18");
}

</style>
