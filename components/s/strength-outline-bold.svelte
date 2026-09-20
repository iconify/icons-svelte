<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="n4avueb2x"/><path class="xxhou8bla"/><path class="u-hehrbeq"/><path class="tum88bbiw"/><path class="t407nkbfi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:strength-outline-bold" {...props}></Icon>
<style>
:global(.n4avueb2x) {
  d: path("M6 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t407nkbfi) {
  d: path("m9 7 3 -3 3 3");
}

:global(.tum88bbiw) {
  d: path("M12 12V4");
}

:global(.u-hehrbeq) {
  d: path("M10 17h4");
}

:global(.xxhou8bla) {
  d: path("M14 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
