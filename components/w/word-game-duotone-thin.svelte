<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rh_yjfbed"/><path class="r8lmp6u5e"/><path class="xyvnrdm2l"/><path class="gszsvr09c"/><path class="s_sj9bjbj"/><path class="izycrzbmp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:word-game-duotone-thin" {...props}></Icon>
<style>
:global(.gszsvr09c) {
  d: path("M14 6v12h7V6Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.izycrzbmp) {
  d: path("M16 14h3");
}

:global(.r8lmp6u5e) {
  fill: currentColor;
  d: path("M14 6v12h7V6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.rh_yjfbed) {
  fill: currentColor;
  d: path("M3 6v12h7V6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s_sj9bjbj) {
  d: path("m4.5 14 2 -2 2 2");
}

:global(.xyvnrdm2l) {
  d: path("M3 6v12h7V6Z");
}

</style>
