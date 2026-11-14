<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qpofv-b0o"/><path class="kq32axa3e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:team-lineup" {...props}></Icon>
<style>
:global(.kq32axa3e) {
  d: path("M8.5 2.5h7v3h-7Zm-.5 8h8m-8 4h8m-8 4h5");
}

:global(.qpofv-b0o) {
  d: path("M4.5 4h15v17.5h-15Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
