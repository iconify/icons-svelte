<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rvub71bbg"/><path class="d5b4fcc2f"/><path class="xd-ovyw0w"/><path class="e5hzi9ldh"/><path class="oscmqi7_r"/><path class="z9ittvbis"/><path class="qvtmo6b3b"/><path class="a46bghb1i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tab-new-duotone-bold" {...props}></Icon>
<style>
:global(.a46bghb1i) {
  d: path("M18 10v6");
}

:global(.d5b4fcc2f) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.e5hzi9ldh) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 10v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.oscmqi7_r) {
  d: path("M2 19V9l2 -2h6l2 2v10");
}

:global(.qvtmo6b3b) {
  d: path("M15 13h6");
}

:global(.rvub71bbg) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 19V9l2 -2h6l2 2v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.xd-ovyw0w) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 13h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

</style>
