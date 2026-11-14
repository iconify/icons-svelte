<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pnlkqbc8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:text-color" {...props}></Icon>
<style>
:global(.pnlkqbc8p) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6 15l6-11.5L18 15m-9.75-4.25h7.5m-11 7.75h14.5a1.25 1.25 0 0 1 1.25 1.25A1.25 1.25 0 0 1 19.25 21H4.75a1.25 1.25 0 0 1-1.25-1.25a1.25 1.25 0 0 1 1.25-1.25");
}

</style>
