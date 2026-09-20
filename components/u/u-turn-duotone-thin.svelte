<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ae6ph_bur"/><path class="gbqtumj_a"/><path class="avsermgoo"/><path class="utl7yebdg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:u-turn-duotone-thin" {...props}></Icon>
<style>
:global(.ae6ph_bur) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 20v-9a6 6 0 0 1 12 0v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.avsermgoo) {
  d: path("M6 20v-9a6 6 0 0 1 12 0v9");
}

:global(.gbqtumj_a) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15 17 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.utl7yebdg) {
  d: path("m15 17 3 3 3 -3");
}

</style>
