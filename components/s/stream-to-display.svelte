<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="l6odb7b5q"/><path class="f9g6b8ivx"/><path class="afk3glbhf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:stream-to-display" {...props}></Icon>
<style>
:global(.afk3glbhf) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12.75h.01");
}

:global(.f9g6b8ivx) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 16.25v4m-3.5 0h7m-5.62-9.62a3 3 0 0 1 4.24 0M7.76 8.51a6 6 0 0 1 8.48 0");
}

:global(.l6odb7b5q) {
  width: 18.5px;
  height: 12.5px;
  x: 2.75px;
  y: 3.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
