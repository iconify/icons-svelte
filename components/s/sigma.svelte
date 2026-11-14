<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ej22w6rlg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:sigma" {...props}></Icon>
<style>
:global(.ej22w6rlg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18 5H6l6 7l-6 7h12");
}

</style>
