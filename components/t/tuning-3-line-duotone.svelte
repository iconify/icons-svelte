<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="h_tsn8bxt"/><circle class="imrhgbc8c"/><circle class="qbe_3qbje"/><path class="gv40cnbhb"/><path class="t0kfsthsf"/><path class="uhbrgbbup"/><path class="zxylmobtl"/><path class="r84xtxbro"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:tuning-3-line-duotone" {...props}></Icon>
<style>
:global(.gv40cnbhb) {
  d: path("M20 12L20 5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.h_tsn8bxt) {
  cx: 12px;
  cy: 12px;
  r: 2px;
}

:global(.imrhgbc8c) {
  cx: 20px;
  cy: 14px;
  r: 2px;
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qbe_3qbje) {
  cx: 4px;
  cy: 10px;
  r: 2px;
}

:global(.r84xtxbro) {
  d: path("M12 10V5M4 5V7.66667");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.t0kfsthsf) {
  d: path("M4 12V19");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.uhbrgbbup) {
  d: path("M12 19V14");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.zxylmobtl) {
  d: path("M20 19L20 16");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
