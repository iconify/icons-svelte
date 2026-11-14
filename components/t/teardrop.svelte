<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y80s3jbmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:teardrop" {...props}></Icon>
<style>
:global(.y80s3jbmy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M20.5 3.5V12A8.5 8.5 0 1 1 12 3.5Z");
}

</style>
