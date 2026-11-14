<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ky8rhmm9y"/><path class="nthnoib9k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:this-way-up" {...props}></Icon>
<style>
:global(.ky8rhmm9y) {
  d: path("M5 4.5h14v15H5ZM12 8v8");
}

:global(.nthnoib9k) {
  d: path("m9 11l3-3l3 3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
