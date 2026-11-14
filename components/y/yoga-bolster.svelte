<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kpptmb-qf"/><path class="cgesaib3l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:yoga-bolster" {...props}></Icon>
<style>
:global(.cgesaib3l) {
  d: path("M3.5 10.25a2.5 4 0 1 0 5 0a2.5 4 0 1 0-5 0Zm-1 7.25h19");
}

:global(.kpptmb-qf) {
  d: path("M6 6.25h12a2.5 4 0 0 1 0 8H6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
