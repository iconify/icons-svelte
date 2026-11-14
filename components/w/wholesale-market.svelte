<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kqlqbrobv"/><path class="vmt-lpbqq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:wholesale-market" {...props}></Icon>
<style>
:global(.kqlqbrobv) {
  d: path("M2.5 20.5V9L12 3.5L21.5 9v11.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vmt-lpbqq) {
  d: path("M7 16.5h5v4H7Zm5 0h5v4h-5Zm-2.5-4h5v4h-5Z");
}

</style>
