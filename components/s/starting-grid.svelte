<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lrxqirb1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:starting-grid" {...props}></Icon>
<style>
:global(.lrxqirb1a) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 3h3.5a1.75 1.75 0 0 1 1.75 1.75v5a1.75 1.75 0 0 1-1.75 1.75h-3.5A1.75 1.75 0 0 1 3.5 9.75v-5A1.75 1.75 0 0 1 5.25 3m10 9.5h3.5a1.75 1.75 0 0 1 1.75 1.75v5A1.75 1.75 0 0 1 18.75 21h-3.5a1.75 1.75 0 0 1-1.75-1.75v-5a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
