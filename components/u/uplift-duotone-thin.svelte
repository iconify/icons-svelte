<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="obeew47lh"/><path class="eziatkq_z"/><path class="i6yllfq7b"/><path class="nanwac02w"/><path class="aut8y9hmn"/><path class="ow_ax0v9r"/><path class="du_3_4tit"/><path class="sgi0qkbzh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:uplift-duotone-thin" {...props}></Icon>
<style>
:global(.aut8y9hmn) {
  d: path("M7 12v7");
}

:global(.du_3_4tit) {
  d: path("M4 21.5h16");
}

:global(.eziatkq_z) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 6v13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i6yllfq7b) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 21.5h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nanwac02w) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 10.5 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.obeew47lh) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 12v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ow_ax0v9r) {
  d: path("M15 6v13");
}

:global(.sgi0qkbzh) {
  d: path("m9 10.5 3 -3");
}

</style>
