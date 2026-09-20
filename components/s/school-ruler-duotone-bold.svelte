<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="j8utnip8g"/><path class="xvabp0bhv"/><path class="m8h6hlbgk"/><path class="uux3anbrn"/><path class="yyqghmoaf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:school-ruler-duotone-bold" {...props}></Icon>
<style>
:global(.j8utnip8g) {
  fill: currentColor;
  d: path("M2 16 16 2l6 6L8 22Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.m8h6hlbgk) {
  d: path("m5 13 3 3");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.uux3anbrn) {
  d: path("m9 9 3 3");
}

:global(.xvabp0bhv) {
  d: path("M2 16 16 2l6 6L8 22Z");
}

:global(.yyqghmoaf) {
  d: path("m13 5 3 3");
}

</style>
