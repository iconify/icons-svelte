<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f2kulnbzp"/><path class="fkwmypbjs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:stroke" {...props}></Icon>
<style>
:global(.f2kulnbzp) {
  d: path("M7 5.75c.5-2 2.75-3 4.75-2.25c1.25-1.25 4-1 5 .5c2.25 0 3.75 1.75 3.5 3.75c1.5 1.25 1.5 3.75.25 5c.25 2.25-1.5 3.75-3.5 3.5c-1 1.5-3.5 2-5 1c-1.75 1-4.25.5-5-1c-2.25.25-4-1.5-3.5-3.5C2.25 11.5 2.25 9 3.75 8c0-1.75 1.5-2.75 3.25-2.25m7.75 12l.75 3.75");
}

:global(.fkwmypbjs) {
  d: path("M5 14c2-1.5 3.5-2 4.75-2.75m3-1.75c1.5-.75 3-1 4.5-2.5m-2 1.5c1 1.25 2.25 2 3.5 2M11.25 8v1.25M9.75 9l.75.75M12.75 12l-.75-.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
