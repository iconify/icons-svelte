<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k4rxhebyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:skate-trainer" {...props}></Icon>
<style>
:global(.k4rxhebyz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 5h5v6l4.5 2.25a2 2 0 0 1 1.5 2V17H8ZM7 21h12.5a1.5 1.5 0 0 0 1.5-1.5M10.5 17v4m6-4v4M8 14H4V2.5");
}

</style>
