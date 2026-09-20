<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="bgz3owcvd"/><path class="vux4gkbhn"/><path class="nj9g-accq"/><path class="axyqg5uel"/><path class="jkuojibnm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:stacked-bar-outline-bold" {...props}></Icon>
<style>
:global(.axyqg5uel) {
  d: path("M16 14v6");
}

:global(.bgz3owcvd) {
  d: path("M8 4v7");
}

:global(.jkuojibnm) {
  d: path("M3 20h18");
}

:global(.nj9g-accq) {
  d: path("M16 8v3");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vux4gkbhn) {
  d: path("M8 14v6");
}

</style>
