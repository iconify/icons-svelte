<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c0vt-nbqz"/><path class="q5t8_9bwl"/><path class="xexl8ib7x"/><path class="e7fjltb5i"/><path class="w08657bnd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:study-group-outline-bold" {...props}></Icon>
<style>
:global(.c0vt-nbqz) {
  d: path("M2 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.e7fjltb5i) {
  d: path("M12 13v8");
}

:global(.q5t8_9bwl) {
  d: path("M16 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.w08657bnd) {
  d: path("M9 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.xexl8ib7x) {
  d: path("M7 15a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H9a2 2 0 0 1 -2 -2Z");
}

</style>
