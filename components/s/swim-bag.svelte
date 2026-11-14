<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j6s7l6bxz"/><path class="ny6m15pqj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:swim-bag" {...props}></Icon>
<style>
:global(.j6s7l6bxz) {
  d: path("M8 7c-5 3-4.5 14 0 14h8c4.5 0 5-11 0-14Zm2 0L8.5 3h7L14 7");
}

:global(.ny6m15pqj) {
  d: path("M7.5 14q2.25-1.5 4.5 0t4.5 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
