<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qoz4a4b4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:sd-card-micro" {...props}></Icon>
<style>
:global(.qoz4a4b4i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 5h6A1.5 1.5 0 0 1 17 6.5V18a1.5 1.5 0 0 1-1.5 1.5h-7A1.5 1.5 0 0 1 7 18V7.5Zm.5 9v3m2-3v3m2-3v3");
}

</style>
