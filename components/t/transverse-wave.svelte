<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rl0xssn0v"/><path class="oojvobb7j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:transverse-wave" {...props}></Icon>
<style>
:global(.oojvobb7j) {
  d: path("M3 18h18m-2.25-2.25L21 18l-2.25 2.25");
}

:global(.rl0xssn0v) {
  d: path("M3 8q2.25-8 4.5 0T12 8t4.5 0T21 8");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
