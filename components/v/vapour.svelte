<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t61gbpaze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:vapour" {...props}></Icon>
<style>
:global(.t61gbpaze) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 20h17M7 16.5q-2.625-3 0-6t0-6m5 12q-2.625-3 0-6t0-6m5 12q-2.625-3 0-6t0-6");
}

</style>
