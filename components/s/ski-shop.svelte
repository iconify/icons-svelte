<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hfzbaxf9c"/><path class="m6hqsgb-c"/><path class="txj_69epb"/><path class="e3b2amb_q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ski-shop" {...props}></Icon>
<style>
:global(.e3b2amb_q) {
  d: path("m21 21.5l-4.25-6.25q-1-1.5-2.5-.5");
}

:global(.hfzbaxf9c) {
  d: path("M3 6.5L4.5 3h15L21 6.5m-18 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m6hqsgb-c) {
  d: path("M4 8.5V21h8.2m7.8-9.4V8.5");
}

:global(.txj_69epb) {
  d: path("M7 21v-7h4v7m4 .5l4.25-6.25q1-1.5 2.5-.5");
}

</style>
