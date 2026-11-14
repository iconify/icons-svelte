<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x_qumib3l"/><path class="a-okhcbyk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:var-review" {...props}></Icon>
<style>
:global(.a-okhcbyk) {
  d: path("m9.75 10l5.75 3.75l-5.75 3.75Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x_qumib3l) {
  d: path("M2.5 7h19v13.5h-19Zm6-4.25L12 7l3.5-4.25");
}

</style>
