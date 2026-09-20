<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="py6kisbqn"/><path class="cdyi--bfo"/><path class="r51b5du2m"/><path class="gujfy_b4w"/><path class="hpm6v1-ys"/><path class="bgz3owcvd"/><path class="vux4gkbhn"/><path class="nj9g-accq"/><path class="axyqg5uel"/><path class="jkuojibnm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:stacked-bar-duotone-bold" {...props}></Icon>
<style>
:global(.axyqg5uel) {
  d: path("M16 14v6");
}

:global(.bgz3owcvd) {
  d: path("M8 4v7");
}

:global(.cdyi--bfo) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 14v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gujfy_b4w) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 14v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hpm6v1-ys) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jkuojibnm) {
  d: path("M3 20h18");
}

:global(.nj9g-accq) {
  d: path("M16 8v3");
}

:global(.py6kisbqn) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 4v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r51b5du2m) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 8v3");
  opacity: var(--svg-opacity--0-2, 0.2);
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
