<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ywch90sba"/><path class="ilk2gccex"/><path class="v35i90uku"/><path class="k2ge1hzsr"/><path class="qqj79abfc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ski-lift-outline-bold" {...props}></Icon>
<style>
:global(.ilk2gccex) {
  d: path("M7 8v4");
}

:global(.k2ge1hzsr) {
  d: path("M15 15v4");
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
