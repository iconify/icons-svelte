<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jszbb1ext"/><path class="ujgggmb5i"/><path class="cjsg0ab2y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:snow-mountain-outline-bold" {...props}></Icon>
<style>
:global(.cjsg0ab2y) {
  d: path("M2 20h20");
}

:global(.jszbb1ext) {
  d: path("m2 18 8 -8 4 4 6 -6 2 2");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ujgggmb5i) {
  d: path("m7 13 3 -3 3 3");
}

</style>
