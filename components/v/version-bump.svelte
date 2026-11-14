<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xcz0x1doi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:version-bump" {...props}></Icon>
<style>
:global(.xcz0x1doi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 7l4.25 12L11 7m6.5 13V4m-3.25 3.25L17.5 4l3.25 3.25");
}

</style>
