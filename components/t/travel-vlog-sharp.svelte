<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="zfp8_lbwb"/><path class="s-ur5pfpm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:travel-vlog-sharp" {...props}></Icon>
<style>
:global(.s-ur5pfpm) {
  d: path("M9 15.5c-1.5-1.25-2.25-2.4-2.25-3.75a2.25 2.25 0 0 1 4.5 0c0 1.35-.75 2.5-2.25 3.75Zm6.25-5.25l6-3v9.5l-6-3");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zfp8_lbwb) {
  d: path("M2.75 6.25h12.5v11.5H2.75z");
}

</style>
