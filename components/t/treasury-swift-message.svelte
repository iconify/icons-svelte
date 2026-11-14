<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ne34zgklx"/><path class="eg9e_xbkj"/><path class="vjt_vebdt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:treasury-swift-message" {...props}></Icon>
<style>
:global(.eg9e_xbkj) {
  d: path("m2.5 7l8.5 6l2.429-1.754M14.25 6.5a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Zm0 0h7.5");
}

:global(.ne34zgklx) {
  d: path("M21.5 12v7.5h-19v-14h8.9");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vjt_vebdt) {
  d: path("M18 2.75c-1.75 1.75-1.75 5.75 0 7.5");
}

</style>
