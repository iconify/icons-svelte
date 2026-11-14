<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iwfu3jbbx"/><path class="rvzpc0-cn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:shampoo-bottle" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iwfu3jbbx) {
  d: path("M7 7.5h4V9l3 2.5V20a1.5 1.5 0 0 1-1.5 1.5h-7A1.5 1.5 0 0 1 4 20v-8.5L7 9Zm2 0v-3H6.5V2.75h7l2 1.75");
}

:global(.rvzpc0-cn) {
  d: path("M8.25 13h1.5a1.5 1.5 0 0 1 1.5 1.5v2a1.5 1.5 0 0 1-1.5 1.5h-1.5a1.5 1.5 0 0 1-1.5-1.5v-2a1.5 1.5 0 0 1 1.5-1.5m8.5-5.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m.75 5.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
