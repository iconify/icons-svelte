<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bx2mexb1z"/><path class="w-esv_mrh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:short-video-save" {...props}></Icon>
<style>
:global(.bx2mexb1z) {
  d: path("M12.7 20.5H3.5v-18h13v8.2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w-esv_mrh) {
  d: path("m8.5 8.5l4 3l-4 3Zm7 5H21V21l-2.75-2l-2.75 2Z");
}

</style>
