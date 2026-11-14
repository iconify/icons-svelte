<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jksggizrl"/><path class="xjxj4ykqy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:store-closed" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jksggizrl) {
  d: path("M3 7.5L4.5 3h15L21 7.5M4.5 10.75V21m15-10.25V21");
}

:global(.xjxj4ykqy) {
  d: path("M3 7.5a4.5 4.5 0 0 0 9 0a4.5 4.5 0 0 0 9 0m-9 0v7m-3 0h6a1.75 1.75 0 0 1 1.75 1.75v2A1.75 1.75 0 0 1 15 20H9a1.75 1.75 0 0 1-1.75-1.75v-2A1.75 1.75 0 0 1 9 14.5m.75 2.75h4.5");
}

</style>
