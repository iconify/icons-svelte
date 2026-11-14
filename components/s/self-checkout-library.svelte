<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z3928acbp"/><path class="ohh13ab8y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:self-checkout-library" {...props}></Icon>
<style>
:global(.ohh13ab8y) {
  d: path("M7.5 16a2.5 2.5 0 0 1 2.5-2.5h6.5M2.5 7V5A2.5 2.5 0 0 1 5 2.5h2m10 0h2A2.5 2.5 0 0 1 21.5 5v2m0 10v2a2.5 2.5 0 0 1-2.5 2.5h-2m-10 0H5A2.5 2.5 0 0 1 2.5 19v-2m2-7h15");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z3928acbp) {
  d: path("M7.5 16V8A2.5 2.5 0 0 1 10 5.5h6.5v13H10A2.5 2.5 0 0 1 7.5 16Z");
}

</style>
