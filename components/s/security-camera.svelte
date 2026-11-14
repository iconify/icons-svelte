<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ndg1f5x6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:security-camera" {...props}></Icon>
<style>
:global(.ndg1f5x6i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.644 2.808l13.523 3.623l-1.811 6.761L1.833 9.569ZM12 13v4h8m.5-3.5v7M6 8h.01");
}

</style>
