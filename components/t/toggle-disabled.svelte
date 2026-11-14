<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hu3v_abqu"/><path class="a9gxfxb1l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:toggle-disabled" {...props}></Icon>
<style>
:global(.a9gxfxb1l) {
  d: path("M5 12a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

:global(.hu3v_abqu) {
  d: path("M8 17.5a5.5 5.5 0 0 1 0-11m8 0a5.5 5.5 0 0 1 0 11m-5.5-11h3m-3 11h3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
