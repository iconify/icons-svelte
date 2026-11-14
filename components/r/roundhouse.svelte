<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m108tcbda"/><path class="nrzgs4qct"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:roundhouse" {...props}></Icon>
<style>
:global(.m108tcbda) {
  d: path("M2.5 19.5v-10q9.5-8.5 19 0v10Z");
}

:global(.nrzgs4qct) {
  d: path("M6 19.5v-5a2 2 0 0 1 4 0v5m4 0v-5a2 2 0 0 1 4 0v5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
