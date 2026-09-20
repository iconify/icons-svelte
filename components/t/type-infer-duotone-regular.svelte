<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cwjlhobnx"/><path class="npvd7ebcg"/><path class="xfirob-xp"/><path class="j5cmolbru"/><path class="i_kjavbri"/><path class="nilwl-6aj"/><path class="qtxvlht3c"/><path class="gl3o38_gx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:type-infer-duotone-regular" {...props}></Icon>
<style>
:global(.cwjlhobnx) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m8.5 3 -5 5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gl3o38_gx) {
  d: path("M8 21h8");
}

:global(.i_kjavbri) {
  d: path("m8.5 3 -5 5 5 5");
}

:global(.j5cmolbru) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 21h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nilwl-6aj) {
  d: path("m15.5 3 5 5 -5 5");
}

:global(.npvd7ebcg) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m15.5 3 5 5 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qtxvlht3c) {
  d: path("M8 17h8");
}

:global(.xfirob-xp) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 17h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
