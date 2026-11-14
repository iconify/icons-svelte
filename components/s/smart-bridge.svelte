<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="io_37tkhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:smart-bridge" {...props}></Icon>
<style>
:global(.io_37tkhb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 11.5h11A3.5 3.5 0 0 1 21 15v1.5a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 16.5V15a3.5 3.5 0 0 1 3.5-3.5m.5 0L5 3m12 8.5L19 3M9 15.75h.01m2.99 0h.01m2.99 0h.01");
}

</style>
