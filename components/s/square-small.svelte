<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ddtgdbc5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:square-small" {...props}></Icon>
<style>
:global(.ddtgdbc5x) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 7h3a3.5 3.5 0 0 1 3.5 3.5v3a3.5 3.5 0 0 1-3.5 3.5h-3A3.5 3.5 0 0 1 7 13.5v-3A3.5 3.5 0 0 1 10.5 7");
}

</style>
