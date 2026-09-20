<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="m9xcm2gjc"/><path class="kjz01rb7i"/><path class="avsermgoo"/><path class="utl7yebdg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:u-turn-duotone-bold" {...props}></Icon>
<style>
:global(.avsermgoo) {
  d: path("M6 20v-9a6 6 0 0 1 12 0v9");
}

:global(.kjz01rb7i) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 17 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m9xcm2gjc) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 20v-9a6 6 0 0 1 12 0v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.utl7yebdg) {
  d: path("m15 17 3 3 3 -3");
}

</style>
