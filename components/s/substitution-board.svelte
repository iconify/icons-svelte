<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ugpso53iv"/><path class="tjth2nzla"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:substitution-board" {...props}></Icon>
<style>
:global(.tjth2nzla) {
  d: path("M5.5 6.25h3.75l-2 6.5m7.5-5.25l2-1.25v6.5");
}

:global(.ugpso53iv) {
  d: path("M2.5 3.5h19v12h-19Zm9.5 12V21m0-17.5v12");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
