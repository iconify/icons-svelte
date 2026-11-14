<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t3dmr2per"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:wine-glass" {...props}></Icon>
<style>
:global(.t3dmr2per) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 3h10v4.5a5 5 0 0 1-10 0Zm5 9.5V21m-4 0h8");
}

</style>
