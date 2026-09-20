<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="as6g9lfvf"/><path class="s2f_5t2iz"/><path class="nbgsfjb6u"/><path class="tr6mw0eac"/><path class="jwnes9bsk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:trophy-cup-outline-thin" {...props}></Icon>
<style>
:global(.as6g9lfvf) {
  d: path("M7 3h10v6c0 4 -2 6 -5 6s-5 -2 -5 -6Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jwnes9bsk) {
  d: path("M8 19h8");
}

:global(.nbgsfjb6u) {
  d: path("M17 5c3 0 4 4 0 5");
}

:global(.s2f_5t2iz) {
  d: path("M7 5c-3 0 -4 4 0 5");
}

:global(.tr6mw0eac) {
  d: path("M12 15v4");
}

</style>
