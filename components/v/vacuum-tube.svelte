<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wixxmolyr"/><path class="gk6llfbgc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:vacuum-tube" {...props}></Icon>
<style>
:global(.gk6llfbgc) {
  d: path("M9.5 15.5v-6h5v6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wixxmolyr) {
  d: path("M6.5 18.5V9a5.5 5.5 0 0 1 11 0v9.5Zm3 0v3m5-3v3");
}

</style>
