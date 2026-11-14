<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jl-2l1bdc"/><path class="s8r7r5hnm"/><path class="r8aju0a9p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:tumble-dryer" {...props}></Icon>
<style>
:global(.jl-2l1bdc) {
  d: path("M3.5 2.5h17v19h-17Zm0 4h17");
}

:global(.r8aju0a9p) {
  d: path("M9.5 13q1.25-1 2.5 0t2.5 0m-5 2.5q1.25-1 2.5 0t2.5 0");
}

:global(.s8r7r5hnm) {
  d: path("M7 14a5 5 0 1 0 10 0a5 5 0 1 0-10 0Zm10-9.5h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
