<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="sgjb9gifn"/><path class="fj1t4gq7w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:smoke-suite-outline-bold" {...props}></Icon>
<style>
:global(.fj1t4gq7w) {
  d: path("m8 16.5 2.5 -2.5 2.5 2.5 2.5 -2.5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sgjb9gifn) {
  d: path("M9 3v7l-5 5v4h16v-4l-5 -5V3Z");
}

</style>
