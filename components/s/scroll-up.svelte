<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mjx34ibpw"/><path class="vh29fpbxk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:scroll-up" {...props}></Icon>
<style>
:global(.mjx34ibpw) {
  d: path("M6.5 17V4.5a2 2 0 0 1 2-2h7a2 2 0 0 1 2 2V17M4 17h16v4.5H4Zm8-3.5V6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vh29fpbxk) {
  d: path("M9.25 8.75L12 6l2.75 2.75");
}

</style>
