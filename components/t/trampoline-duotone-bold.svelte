<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jzeve79sx"/><path class="qewuh9pgi"/><path class="izztv2bmh"/><path class="llep1obfh"/><path class="yhxg0gb1u"/><path class="ifnz35boy"/><path class="wp14ejvwu"/><path class="ymw3aibdo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:trampoline-duotone-bold" {...props}></Icon>
<style>
:global(.ifnz35boy) {
  d: path("M5 12v8");
}

:global(.izztv2bmh) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 12v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jzeve79sx) {
  fill: currentColor;
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.llep1obfh) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19 12v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qewuh9pgi) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 11c4 3 14 3 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wp14ejvwu) {
  d: path("M19 12v8");
}

:global(.yhxg0gb1u) {
  d: path("M3 11c4 3 14 3 18 0");
}

:global(.ymw3aibdo) {
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
