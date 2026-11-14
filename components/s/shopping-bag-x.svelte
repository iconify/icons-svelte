<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bpjm8y99j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:shopping-bag-x" {...props}></Icon>
<style>
:global(.bpjm8y99j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 8h14l-.25 4.25h-4.5a2 2 0 0 0-2 2V21h-4.5a2 2 0 0 1-2-2Zm3.5 0V6.5a3.5 3.5 0 0 1 7 0V8m0 7.5l5 5m0-5l-5 5");
}

</style>
