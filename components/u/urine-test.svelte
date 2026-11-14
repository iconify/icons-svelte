<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jlw-4bbqw"/><path class="krtfmdh_e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:urine-test" {...props}></Icon>
<style>
:global(.jlw-4bbqw) {
  d: path("m4.5 9.5l2 10.5c.15.9.9 1.5 1.75 1.5h7.5c.85 0 1.6-.6 1.75-1.5l2-10.5M6 14h1.8m9.1 0H18");
}

:global(.krtfmdh_e) {
  d: path("m14.985 2.409l2.819 1.026l-4.789 13.156l-2.819-1.026Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
