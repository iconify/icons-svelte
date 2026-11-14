<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fokybdc7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:walking-stick" {...props}></Icon>
<style>
:global(.fokybdc7h) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 6V5a2 2 0 0 1 2-2h2.5v14.5M9.25 21l.75-3.5h5l.75 3.5");
}

</style>
