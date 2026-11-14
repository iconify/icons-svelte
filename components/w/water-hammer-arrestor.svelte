<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="acol-ccpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:water-hammer-arrestor" {...props}></Icon>
<style>
:global(.acol-ccpj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 15h19v5h-19ZM8 12V6.5a4 4 0 0 1 8 0V12Zm2.5 0v3m3-3v3M5 13v9m14-9v9");
}

</style>
