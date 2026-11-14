<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ersy5zbyg"/><path class="j8ni8ik0d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:valve-chamber" {...props}></Icon>
<style>
:global(.ersy5zbyg) {
  d: path("M2.5 2.5h19v19h-19Zm0 12.5h7m5 0h7");
}

:global(.j8ni8ik0d) {
  d: path("M9.5 15a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm2.5-2.5V8M9 8h6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
