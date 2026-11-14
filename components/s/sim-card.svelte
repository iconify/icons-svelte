<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h_pf9yb8w"/><path class="ok1vbhbyv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:sim-card" {...props}></Icon>
<style>
:global(.h_pf9yb8w) {
  d: path("M5 2.5h9.5L19 7v14.5H5Z");
}

:global(.ok1vbhbyv) {
  d: path("M8 10h8v8.5H8Zm0 4.25h8");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
