<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s63e1easn"/><path class="kq0hl2bct"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:tab-pin" {...props}></Icon>
<style>
:global(.kq0hl2bct) {
  d: path("M10 7h4v3.5l2 3H8l2-3Zm2 6.5v5");
}

:global(.s63e1easn) {
  d: path("M2.5 19.5h2V6a2 2 0 0 1 2-2h11a2 2 0 0 1 2 2v13.5h2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
