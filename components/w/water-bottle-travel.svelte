<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ci4aqtg0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:water-bottle-travel" {...props}></Icon>
<style>
:global(.ci4aqtg0f) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 3.5h4V6c0 1 3 1.5 3 4v9a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2v-9c0-2.5 3-3 3-4ZM7 14h10");
}

</style>
