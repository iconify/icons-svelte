<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xj3395b8f"/><path class="jz0b4rbqp"/><path class="st2iv5bfu"/><path class="d2pq28uem"/><path class="th2thdcjq"/><path class="acx0wnihd"/><path class="f8ull7b3a"/><path class="fg8libqda"/><path class="pw61xnbei"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tow-truck-duotone-bold" {...props}></Icon>
<style>
:global(.acx0wnihd) {
  d: path("M21.5 6.5a2.5 2.5 0 0 1 -5 0");
}

:global(.d2pq28uem) {
  d: path("M2 17V8a2 2 0 0 1 2 -2h5v11Z");
}

:global(.f8ull7b3a) {
  d: path("M9 13h13v4H9");
}

:global(.fg8libqda) {
  d: path("M4 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.jz0b4rbqp) {
  fill: currentColor;
  d: path("M4 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.pw61xnbei) {
  d: path("M16 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.st2iv5bfu) {
  fill: currentColor;
  d: path("M16 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.th2thdcjq) {
  d: path("M9 10h4l6 -6");
}

:global(.xj3395b8f) {
  fill: currentColor;
  d: path("M2 17V8a2 2 0 0 1 2 -2h5v11Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
