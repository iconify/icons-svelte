<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gvc65tz1p"/><path class="skf2dub_m"/><path class="oyjqk5bct"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:separator-horizontal-broken" {...props}></Icon>
<style>
:global(.gvc65tz1p) {
  d: path("M13.5 4.5L12 3L6 9M16.5 7.5L18 9");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oyjqk5bct) {
  d: path("M22 12H2");
}

:global(.skf2dub_m) {
  d: path("M13.5 19.5L12 21L6 15M16.5 16.5L18 15");
}

</style>
