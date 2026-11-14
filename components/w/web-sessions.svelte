<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d04xtmf9q"/><path class="hvhsg7bal"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:web-sessions" {...props}></Icon>
<style>
:global(.d04xtmf9q) {
  d: path("M2.5 7.5H18v13H2.5Z");
}

:global(.hvhsg7bal) {
  d: path("M6.5 7.5v-2a2 2 0 0 1 2-2h11a2 2 0 0 1 2 2v9a2 2 0 0 1-2 2H18m-15.5-5H18m-12.75-2h.01m2.49 0h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
