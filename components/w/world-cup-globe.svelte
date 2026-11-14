<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fc5f16b8b"/><path class="jgfmqvhzc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:world-cup-globe" {...props}></Icon>
<style>
:global(.fc5f16b8b) {
  d: path("M5.5 8.5a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0M12 15v2.75m-3.25 1.875l.373-.932a1.5 1.5 0 0 1 1.393-.943h2.968a1.5 1.5 0 0 1 1.393.943l.373.932a1.367 1.367 0 0 1-1.269 1.875h-3.962a1.367 1.367 0 0 1-1.269-1.875");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jgfmqvhzc) {
  d: path("M9.25 8.5a2.75 6.5 0 1 0 5.5 0a2.75 6.5 0 1 0-5.5 0m-3.75 0h13");
}

</style>
