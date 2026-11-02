<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e1fgqy-sc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:waves-duotone-sharp" {...props}></Icon>
<style>
:global(.e1fgqy-sc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 7c2 0 2-2 4-2s2 2 4 2s2-2 4-2s2 2 4 2M4 19c2 0 2-2 4-2s2 2 4 2s2-2 4-2s2 2 4 2M4 13c2 0 2-2 4-2s2 2 4 2s2-2 4-2s2 2 4 2");
}

</style>
