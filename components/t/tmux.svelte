<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nf96v8b3i"/><path class="s4-_4xbpk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:tmux" {...props}></Icon>
<style>
:global(.nf96v8b3i) {
  d: path("M2.5 3.5h19v17h-19Zm9.5 0v17m0-8.5h9.5");
}

:global(.s4-_4xbpk) {
  d: path("M5.5 9.5L8 12l-2.5 2.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
