<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z22p2s54p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:zodiac-aquarius-duotone" {...props}></Icon>
<style>
:global(.z22p2s54p) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m3 10l2-2a1.414 1.414 0 0 1 2 0l1 1a1.414 1.414 0 0 0 2 0l1-1a1.414 1.414 0 0 1 2 0l1 1a1.414 1.414 0 0 0 2 0l1-1a1.414 1.414 0 0 1 2 0l2 2M3 17l2-2a1.414 1.414 0 0 1 2 0l1 1a1.414 1.414 0 0 0 2 0l1-1a1.414 1.414 0 0 1 2 0l1 1a1.414 1.414 0 0 0 2 0l1-1a1.414 1.414 0 0 1 2 0l2 2");
}

</style>
