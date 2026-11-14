<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tqqdzd8fz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:toilet-gender-neutral" {...props}></Icon>
<style>
:global(.tqqdzd8fz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 4.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M12 9H9.5A1.5 1.5 0 0 0 8 10.5v11h4Zm0 0h2l3.5 7.5H12m2.75 0v5");
}

</style>
