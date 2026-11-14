<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n00q00bzr"/><path class="s8fa3obus"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:vr-headset-wireless" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n00q00bzr) {
  d: path("M5 9h11a2.5 2.5 0 0 1 2.5 2.5v6A2.5 2.5 0 0 1 16 20h-3a2.5 2.5 0 0 0-5 0H5a2.5 2.5 0 0 1-2.5-2.5v-6A2.5 2.5 0 0 1 5 9");
}

:global(.s8fa3obus) {
  d: path("M5.25 13.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m7 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m4.25-8.75a2.5 2.5 0 0 1 2.5 2.5M16.5 2a5.25 5.25 0 0 1 5.25 5.25");
}

</style>
