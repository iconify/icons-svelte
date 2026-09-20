<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hr6yi9b8a"/><path class="d7hs-sz5l"/><path class="viv5gg8xx"/><path class="r_1159bkb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:small-language-model-duotone-regular" {...props}></Icon>
<style>
:global(.d7hs-sz5l) {
  fill: currentColor;
  d: path("M11.5 6H14a3 3 0 0 1 3 3v5a3 3 0 0 1 -3 3H9a3 3 0 0 1 -3 -3V9l3 -3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hr6yi9b8a) {
  fill: currentColor;
  d: path("M2 4a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.r_1159bkb) {
  d: path("M11.5 6H14a3 3 0 0 1 3 3v5a3 3 0 0 1 -3 3H9a3 3 0 0 1 -3 -3V9l3 -3Z");
}

:global(.viv5gg8xx) {
  d: path("M2 4a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
