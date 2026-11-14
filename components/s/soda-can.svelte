<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s5hsg3bvx"/><path class="n41ehcbpp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:soda-can" {...props}></Icon>
<style>
:global(.n41ehcbpp) {
  d: path("M5.5 5.75V18.5a6.5 2.5 0 0 0 13 0V5.75m-8 0h3");
}

:global(.s5hsg3bvx) {
  d: path("M5.5 5.75a6.5 2.75 0 1 0 13 0a6.5 2.75 0 1 0-13 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
