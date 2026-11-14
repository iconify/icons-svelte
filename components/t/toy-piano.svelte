<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f9_gy2b0g"/><path class="dk5wt9tbn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:toy-piano" {...props}></Icon>
<style>
:global(.dk5wt9tbn) {
  d: path("M6 9v3.5h2.5V9m-1.25 3.5V17M12 9v8m3.5-8v3.5H18V9m-1.25 3.5V17M4.5 17v3.5m15-3.5v3.5");
}

:global(.f9_gy2b0g) {
  d: path("M2.5 4h19v13h-19Zm0 5h19");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
