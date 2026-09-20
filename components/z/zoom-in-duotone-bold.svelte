<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="plw-owhdh"/><path class="yjc9h6oua"/><path class="nfad3gbna"/><path class="xf6rxlb8o"/><path class="ffw_pwyfz"/><path class="kfdmhd64i"/><path class="wj4ljftik"/><path class="g-zzhsbrv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:zoom-in-duotone-bold" {...props}></Icon>
<style>
:global(.ffw_pwyfz) {
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
}

:global(.g-zzhsbrv) {
  d: path("M7 10h6");
}

:global(.kfdmhd64i) {
  d: path("m15 15 6 6");
}

:global(.nfad3gbna) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 7v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.plw-owhdh) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wj4ljftik) {
  d: path("M10 7v6");
}

:global(.xf6rxlb8o) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 10h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yjc9h6oua) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 15 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
