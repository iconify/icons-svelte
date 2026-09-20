<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="z1ra8bb5p"/><path class="f-7nb_bpw"/><path class="ilm81zbkk"/><path class="n74qqnw0j"/><path class="to02llleg"/><path class="jroakeb3a"/><path class="iup9trbmr"/><path class="u7m7z6ojw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:savepoint-duotone-regular" {...props}></Icon>
<style>
:global(.f-7nb_bpw) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 4H3v16h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ilm81zbkk) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 4h4v16h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.iup9trbmr) {
  d: path("M12 6v4");
}

:global(.jroakeb3a) {
  d: path("M17 4h4v16h-4");
}

:global(.n74qqnw0j) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 6v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.to02llleg) {
  d: path("M7 4H3v16h4");
}

:global(.u7m7z6ojw) {
  d: path("M10 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.z1ra8bb5p) {
  fill: currentColor;
  d: path("M10 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
