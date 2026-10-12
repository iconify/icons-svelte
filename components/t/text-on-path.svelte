<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8hofub4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:text-on-path" {...props}></Icon>
<style>
:global(.t8hofub4w) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.45 12.35l-1.2-6.4l5.4 3.65M4 9.95l2.6-1.7m5.2-5.5l1.05 5.4m-.45-2.2a2.25 2.25 0 1 0 4.4-.85a2.25 2.25 0 1 0-4.4.85m-9.65 13.3c4-6.5 10-9 18.5-9");
}

</style>
