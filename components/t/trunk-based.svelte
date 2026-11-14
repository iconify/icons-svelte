<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ak2n4gnrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:trunk-based" {...props}></Icon>
<style>
:global(.ak2n4gnrz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5v19M3.25 6a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m4 1.5l4.75 4m4.25-1a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m.5 1.5L12 16");
}

</style>
