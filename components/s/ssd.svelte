<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="s52io4hsg"/><rect class="al16hobra"/><path class="yehlk-qlx"/><path class="hv7qdkb8s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ssd" {...props}></Icon>
<style>
:global(.al16hobra) {
  width: 5px;
  height: 3.5px;
  x: 5.75px;
  y: 10.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 0.75px;
}

:global(.hv7qdkb8s) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.5 12h.01");
}

:global(.s52io4hsg) {
  width: 18.5px;
  height: 8.5px;
  x: 2.75px;
  y: 7.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.yehlk-qlx) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.5 12H16");
}

</style>
