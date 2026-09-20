<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xyvnrdm2l"/><path class="gszsvr09c"/><path class="s_sj9bjbj"/><path class="izycrzbmp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:word-game-outline-regular" {...props}></Icon>
<style>
:global(.gszsvr09c) {
  d: path("M14 6v12h7V6Z");
}

:global(.izycrzbmp) {
  d: path("M16 14h3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.s_sj9bjbj) {
  d: path("m4.5 14 2 -2 2 2");
}

:global(.xyvnrdm2l) {
  d: path("M3 6v12h7V6Z");
}

</style>
