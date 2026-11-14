<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n18kas0im"/><path class="sj6ner4xr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:unit-economics" {...props}></Icon>
<style>
:global(.n18kas0im) {
  d: path("M11.454 17.489L10.5 18l-7-3.75v-8l7-3.75l7 3.75v5.159");
}

:global(.sj6ner4xr) {
  d: path("m3.5 6.25l7 3.75l7-3.75m-7 3.75v8m3.75-3.75H18L21.75 18L18 21.75L14.25 18Zm3 3h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
