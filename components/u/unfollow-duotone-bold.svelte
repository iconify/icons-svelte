<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qhdq2dbof"/><path class="ejfmpibyt"/><path class="fgh6wnb3a"/><path class="p8a31xr4o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:unfollow-duotone-bold" {...props}></Icon>
<style>
:global(.ejfmpibyt) {
  d: path("M7 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.fgh6wnb3a) {
  d: path("M6 17a4 4 0 0 1 8 0");
}

:global(.p8a31xr4o) {
  d: path("M16 12h6");
}

:global(.qhdq2dbof) {
  fill: currentColor;
  d: path("M7 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
