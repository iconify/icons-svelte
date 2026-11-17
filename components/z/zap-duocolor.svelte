<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m5pc0qpnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:zap-duocolor" {...props}></Icon>
<style>
:global(.m5pc0qpnd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m9.375 8.5l-3.752 4.717A.482.482 0 0 0 6 14h3.25a1 1 0 0 1 1 1v5c0 .33.417.476.623.217l7.504-9.434A.482.482 0 0 0 18 10h-3.25a1 1 0 0 1-1-1V4a.35.35 0 0 0-.623-.217z");
}

</style>
