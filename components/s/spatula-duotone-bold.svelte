<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="a7_9wnfxj"/><path class="gvgmi5cyl"/><path class="mcs12xbpj"/><path class="ubusnobws"/><path class="e7fjltb5i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:spatula-duotone-bold" {...props}></Icon>
<style>
:global(.a7_9wnfxj) {
  fill: currentColor;
  d: path("M6 6h12v7H6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.e7fjltb5i) {
  d: path("M12 13v8");
}

:global(.gvgmi5cyl) {
  d: path("M6 6h12v7H6Z");
}

:global(.mcs12xbpj) {
  d: path("M10 8v3");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ubusnobws) {
  d: path("M14 8v3");
}

</style>
