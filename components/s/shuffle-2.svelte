<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fq6jk4b8t"/><path class="fea7n9bfx"/><path class="div1mjs6h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:shuffle-2" {...props}></Icon>
<style>
:global(.div1mjs6h) {
  d: path("m18.5 14l3 3l-3 3");
}

:global(.fea7n9bfx) {
  d: path("M2.5 7H6c5 0 7 10 12 10h3.5m-3-13l3 3l-3 3");
}

:global(.fq6jk4b8t) {
  d: path("M2.5 17H6c5 0 7-10 12-10h3.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
