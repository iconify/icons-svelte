<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pq5xezbds"/><path class="q24-p2btr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:swim-paddles" {...props}></Icon>
<style>
:global(.pq5xezbds) {
  d: path("M3 3.5h7.5L9 17.5H4.5Zm10.5 0H21l-1.5 14H15Z");
}

:global(.q24-p2btr) {
  d: path("M6.75 15.25a2.25 2.25 0 0 1 0 4.5m10.5-4.5a2.25 2.25 0 0 1 0 4.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
