<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l087an1gy"/><path class="gllpxrb_n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:tax-house" {...props}></Icon>
<style>
:global(.gllpxrb_n) {
  d: path("M5 9v11a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1V9m-9.75 9l5.5-6.25m-5 1h.01M14.25 17h.01");
}

:global(.l087an1gy) {
  d: path("M2.5 11L12 3l9.5 8");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
