<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fyvf420mr"/><path class="c74kujgny"/><path class="quidtccfi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:stew-outline-bold" {...props}></Icon>
<style>
:global(.c74kujgny) {
  d: path("m14 13 5 -5");
}

:global(.fyvf420mr) {
  d: path("M4 11h16c0 5 -4 9 -8 9s-8 -4 -8 -9");
}

:global(.quidtccfi) {
  d: path("M9 9c2 -2 0 -4 2 -6");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
