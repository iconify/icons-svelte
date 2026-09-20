<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rv-s8188y"/><path class="hwdq41llx"/><path class="qamt0gbak"/><path class="ivhcn-dzy"/><path class="i_kjavbri"/><path class="nilwl-6aj"/><path class="qtxvlht3c"/><path class="gl3o38_gx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:type-infer-duotone-bold" {...props}></Icon>
<style>
:global(.gl3o38_gx) {
  d: path("M8 21h8");
}

:global(.hwdq41llx) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15.5 3 5 5 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.i_kjavbri) {
  d: path("m8.5 3 -5 5 5 5");
}

:global(.ivhcn-dzy) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 21h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nilwl-6aj) {
  d: path("m15.5 3 5 5 -5 5");
}

:global(.qamt0gbak) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 17h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qtxvlht3c) {
  d: path("M8 17h8");
}

:global(.rv-s8188y) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m8.5 3 -5 5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
