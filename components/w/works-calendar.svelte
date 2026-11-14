<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r8vjxsb1w"/><path class="orrdkzbqo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:works-calendar" {...props}></Icon>
<style>
:global(.orrdkzbqo) {
  d: path("M21.75 16.75a3 3 0 1 1-3-3M16.5 19L14 21.5");
}

:global(.r8vjxsb1w) {
  d: path("M10.6 21H3.5V4.5h17v6.4M8 2.5v4m8-4v4m-12.5 3h17");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
