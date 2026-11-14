<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lnjctw_uj"/><path class="l_lolebqr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:spirits-cask" {...props}></Icon>
<style>
:global(.l_lolebqr) {
  d: path("M8.5 5q-1.5 7 0 14m7-14q1.5 7 0 14M12 12h.01");
}

:global(.lnjctw_uj) {
  d: path("M5 6q7-2.5 14 0q2.5 6 0 12q-7 2.5-14 0q-2.5-6 0-12Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
