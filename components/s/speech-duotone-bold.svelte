<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="j4z1smu9o"/><path class="oec57-4mx"/><path class="cs9f_sbcc"/><path class="c664ux15j"/><path class="yjzas4brk"/><path class="lbz2yq5no"/><path class="el0n_ccnv"/><path class="h7bcztycq"/><path class="cg-q-7bgo"/><path class="om2raabrv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:speech-duotone-bold" {...props}></Icon>
<style>
:global(.c664ux15j) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cg-q-7bgo) {
  d: path("M16 3v18");
}

:global(.cs9f_sbcc) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.el0n_ccnv) {
  d: path("M8 5v14");
}

:global(.h7bcztycq) {
  d: path("M12 8v8");
}

:global(.j4z1smu9o) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lbz2yq5no) {
  d: path("M4 9v6");
}

:global(.oec57-4mx) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.om2raabrv) {
  d: path("M20 10v4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.yjzas4brk) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M20 10v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
