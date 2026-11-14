<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="obv2n6bhx"/><path class="jyfz5jbno"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:spotlight" {...props}></Icon>
<style>
:global(.jyfz5jbno) {
  d: path("M9 6h6l1 7H8Zm.5 10L7 21.5m7.5-5.5l2.5 5.5");
}

:global(.obv2n6bhx) {
  d: path("M5.5 8.5V3h13v5.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
