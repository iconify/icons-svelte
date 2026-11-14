<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wb-3accoe"/><path class="l-ggnpg7i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:smartphone-notch" {...props}></Icon>
<style>
:global(.l-ggnpg7i) {
  d: path("M9 2.5v2a1 1 0 0 0 1 1h4a1 1 0 0 0 1-1v-2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wb-3accoe) {
  d: path("M6 2.5h12v19H6ZM10.5 18h3");
}

</style>
