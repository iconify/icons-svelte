<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ucz-wqkxp"/><path class="aiv48bw3s"/><path class="gt3empbzf"/><path class="uzrr--bsw"/><path class="pldoi_k0z"/><path class="s-mi-tbrv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:span-tool-duotone-bold" {...props}></Icon>
<style>
:global(.aiv48bw3s) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 11h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gt3empbzf) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 17h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pldoi_k0z) {
  d: path("M7 11h11");
}

:global(.s-mi-tbrv) {
  d: path("M10 17h11");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ucz-wqkxp) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 5h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.uzrr--bsw) {
  d: path("M3 5h9");
}

</style>
