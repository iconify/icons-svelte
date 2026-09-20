<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i6mxeiyqr"/><path class="dk2_9r6pl"/><path class="mm3_5jlsl"/><path class="n4vthobpf"/><path class="ujte2fbml"/><path class="exx4qg62z"/><path class="o8od38cnm"/><path class="z5iv6lbtc"/><path class="xaedo1bnv"/><path class="omq19fbzw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sunset-header-duotone-regular" {...props}></Icon>
<style>
:global(.dk2_9r6pl) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 18h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.exx4qg62z) {
  d: path("M7 15a5 5 0 0 1 10 0");
}

:global(.i6mxeiyqr) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 15a5 5 0 0 1 10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mm3_5jlsl) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 4.5V7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.n4vthobpf) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m5 8 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o8od38cnm) {
  d: path("M4 18h16");
}

:global(.omq19fbzw) {
  d: path("m19 8 -2 2");
}

:global(.ujte2fbml) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m19 8 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xaedo1bnv) {
  d: path("m5 8 2 2");
}

:global(.z5iv6lbtc) {
  d: path("M12 4.5V7");
}

</style>
