<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u9r3av8kb"/><path class="giz1fi7ar"/><path class="xf6vt8iwe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:timeline-layout" {...props}></Icon>
<style>
:global(.giz1fi7ar) {
  fill: currentColor;
  d: path("M10.5 7a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm0 5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm0 5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

:global(.u9r3av8kb) {
  d: path("M2.5 2.5h19v19h-19Zm9.5 3v13");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xf6vt8iwe) {
  d: path("M12 7h6.5m-13 5H12m0 5h6.5");
}

</style>
