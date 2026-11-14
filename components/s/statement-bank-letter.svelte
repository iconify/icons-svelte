<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o72zbacef"/><path class="na5ya-yuf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:statement-bank-letter" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.na5ya-yuf) {
  d: path("m9.75 7.5l1.329-1.034a1.5 1.5 0 0 1 1.842 0L14.25 7.5a.978.978 0 0 1-.6 1.75h-3.3a.978.978 0 0 1-.6-1.75M8 12.5h8m-8 3h8m-8 3h4");
}

:global(.o72zbacef) {
  d: path("M8.875 2.5h6.25A4.375 4.375 0 0 1 19.5 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375h-6.25A4.375 4.375 0 0 1 4.5 17.125V6.875A4.375 4.375 0 0 1 8.875 2.5");
}

</style>
