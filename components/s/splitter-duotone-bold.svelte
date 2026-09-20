<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="wc2iww91l"/><path class="we519kbrq"/><path class="eysw87xdb"/><path class="jcxg2bbvb"/><path class="fyyr_6-1m"/><path class="ue-dwjbmw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:splitter-duotone-bold" {...props}></Icon>
<style>
:global(.eysw87xdb) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m10 12 4 4h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fyyr_6-1m) {
  d: path("m10 12 4 -4h7");
}

:global(.jcxg2bbvb) {
  d: path("M2 12h8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ue-dwjbmw) {
  d: path("m10 12 4 4h7");
}

:global(.wc2iww91l) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.we519kbrq) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m10 12 4 -4h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
