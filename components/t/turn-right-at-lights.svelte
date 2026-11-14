<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o0vz28bru"/><path class="ht7xlcczt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:turn-right-at-lights" {...props}></Icon>
<style>
:global(.ht7xlcczt) {
  d: path("M18.25 7.25L21 10l-2.75 2.75M3 2.5h6V15H3Zm3 3h.01M6 8.75h.01M6 12h.01");
}

:global(.o0vz28bru) {
  d: path("M13 21.5v-8a3.5 3.5 0 0 1 3.5-3.5H21");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
