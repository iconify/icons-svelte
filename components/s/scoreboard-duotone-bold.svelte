<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zkfw7-bju"/><path class="r35682biw"/><path class="g4h6r4ykz"/><path class="fopjp5vkk"/><path class="di4vjgyye"/><path class="xwm0hzbem"/><path class="vhf3_kexp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:scoreboard-duotone-bold" {...props}></Icon>
<style>
:global(.di4vjgyye) {
  d: path("M5 12h5");
}

:global(.fopjp5vkk) {
  d: path("M5 8h5");
}

:global(.g4h6r4ykz) {
  d: path("M12 4v12");
}

:global(.r35682biw) {
  d: path("M3 6a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vhf3_kexp) {
  d: path("M12 16v5");
}

:global(.xwm0hzbem) {
  d: path("M14 10h5");
}

:global(.zkfw7-bju) {
  fill: currentColor;
  d: path("M3 6a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
