<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jcxg2bbvb"/><path class="fyyr_6-1m"/><path class="ue-dwjbmw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:splitter-outline-thin" {...props}></Icon>
<style>
:global(.fyyr_6-1m) {
  d: path("m10 12 4 -4h7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jcxg2bbvb) {
  d: path("M2 12h8");
}

:global(.ue-dwjbmw) {
  d: path("m10 12 4 4h7");
}

</style>
