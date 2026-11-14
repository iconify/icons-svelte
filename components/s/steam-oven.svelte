<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rnp9bpbao"/><path class="f87wm-bnp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:steam-oven" {...props}></Icon>
<style>
:global(.f87wm-bnp) {
  d: path("M9.5 16.25a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-.5-11C7.75 4.25 10.25 3 9 2m6 3.25C13.75 4.25 16.25 3 15 2");
}

:global(.rnp9bpbao) {
  d: path("M3 8h18v13.5H3Zm0 3h18");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
