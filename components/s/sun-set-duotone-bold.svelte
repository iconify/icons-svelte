<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fb_14tbom"/><path class="d5b4fcc2f"/><path class="ov7oc5bao"/><path class="u3-639g4d"/><path class="eu2so4bxo"/><path class="z9ittvbis"/><path class="fd_pyz_no"/><path class="uh7f2-ziy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sun-set-duotone-bold" {...props}></Icon>
<style>
:global(.d5b4fcc2f) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.eu2so4bxo) {
  d: path("M7 16a5 5 0 0 1 10 0");
}

:global(.fb_14tbom) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 16a5 5 0 0 1 10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fd_pyz_no) {
  d: path("M12 5v4");
}

:global(.ov7oc5bao) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 5v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.u3-639g4d) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9.5 6.5 12 9l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.uh7f2-ziy) {
  d: path("M9.5 6.5 12 9l2.5 -2.5");
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

</style>
