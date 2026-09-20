<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ep8nfwy5e"/><path class="tidwjccky"/><path class="mdhwrnb_u"/><path class="x_1pk7qez"/><path class="nebfuhbln"/><path class="b8yphbcwk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:wedding-duotone-bold" {...props}></Icon>
<style>
:global(.b8yphbcwk) {
  d: path("m10 7 2 -2 2 2 -2 2Z");
}

:global(.ep8nfwy5e) {
  fill: currentColor;
  d: path("M4 14a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.mdhwrnb_u) {
  fill: currentColor;
  d: path("m10 7 2 -2 2 2 -2 2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nebfuhbln) {
  d: path("M12 14a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tidwjccky) {
  fill: currentColor;
  d: path("M12 14a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.x_1pk7qez) {
  d: path("M4 14a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

</style>
