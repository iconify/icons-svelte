<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="crzn5obfu"/><path class="ymp2b4b6u"/><path class="v5he4mb3o"/><path class="c0j5uhb3y"/><path class="w0sebyb3m"/><path class="epr-ge8_k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:shield-config-duotone-bold" {...props}></Icon>
<style>
:global(.c0j5uhb3y) {
  d: path("M13.5 7.5v4");
}

:global(.crzn5obfu) {
  fill: currentColor;
  d: path("M15 5h5v8l-8 8 -8 -8V5h5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.epr-ge8_k) {
  d: path("M10.5 11.5v4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.v5he4mb3o) {
  d: path("M9 9.5h6");
}

:global(.w0sebyb3m) {
  d: path("M9 13.5h6");
}

:global(.ymp2b4b6u) {
  d: path("M15 5h5v8l-8 8 -8 -8V5h5");
}

</style>
