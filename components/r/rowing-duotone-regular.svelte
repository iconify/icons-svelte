<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nhdek5nuo"/><path class="eapwvqbey"/><path class="dui-9ojgu"/><path class="q5jw2tb7h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:rowing-duotone-regular" {...props}></Icon>
<style>
:global(.dui-9ojgu) {
  d: path("M7 12 3 8");
}

:global(.eapwvqbey) {
  d: path("M3 13h18c-1 4 -4 7 -9 7s-8 -3 -9 -7");
}

:global(.nhdek5nuo) {
  fill: currentColor;
  d: path("M3 13h18c-1 4 -4 7 -9 7s-8 -3 -9 -7");
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

:global(.q5jw2tb7h) {
  d: path("m17 12 4 -4");
}

</style>
