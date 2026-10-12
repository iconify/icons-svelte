<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nmv32cbob"/><circle class="yyexh0zlp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:table-tennis" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nmv32cbob) {
  d: path("M2.75 13h18.5M5 13v8.25M19 13v8.25m-7-11.5V13");
}

:global(.yyexh0zlp) {
  cx: 16.5px;
  cy: 6.5px;
  r: 1.75px;
}

</style>
