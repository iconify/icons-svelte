<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qmsfw7b_p"/><path class="pbj590rgm"/><path class="z8yjphbma"/><path class="sx1m0u7ew"/><path class="ftej-1ggr"/><path class="p_xsqcbww"/><path class="o3x_gzblq"/><path class="ffs26fbkv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tuning-fork-duotone-thin" {...props}></Icon>
<style>
:global(.ffs26fbkv) {
  d: path("M12 17v4");
}

:global(.ftej-1ggr) {
  d: path("M8 3v10");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o3x_gzblq) {
  d: path("m8 13 4 4 4 -4");
}

:global(.p_xsqcbww) {
  d: path("M16 3v10");
}

:global(.pbj590rgm) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 3v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qmsfw7b_p) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 3v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.sx1m0u7ew) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 17v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z8yjphbma) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m8 13 4 4 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
