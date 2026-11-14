<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b37bn9b6s"/><path class="ohj1hkepv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:statement-paperless" {...props}></Icon>
<style>
:global(.b37bn9b6s) {
  d: path("M11.3 21.5H4.5v-19h15v9.6M8 7h8m-8 3.5h8M8 14h3.5");
}

:global(.ohj1hkepv) {
  d: path("M15 21.25c0-4.25 2-6.25 6.25-6.5c0 4.25-2.25 6.5-6.25 6.5Zm0 0L18.25 18");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
