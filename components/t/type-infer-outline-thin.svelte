<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i_kjavbri"/><path class="nilwl-6aj"/><path class="qtxvlht3c"/><path class="gl3o38_gx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:type-infer-outline-thin" {...props}></Icon>
<style>
:global(.gl3o38_gx) {
  d: path("M8 21h8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i_kjavbri) {
  d: path("m8.5 3 -5 5 5 5");
}

:global(.nilwl-6aj) {
  d: path("m15.5 3 5 5 -5 5");
}

:global(.qtxvlht3c) {
  d: path("M8 17h8");
}

</style>
