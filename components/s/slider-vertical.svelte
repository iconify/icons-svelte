<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xros0mb-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:slider-vertical" {...props}></Icon>
<style>
:global(.xros0mb-o) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3v8.5m0 7V21m-3-6a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
