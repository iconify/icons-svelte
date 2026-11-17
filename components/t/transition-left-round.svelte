<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x7y4moezt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:transition-left-round" {...props}></Icon>
<style>
:global(.x7y4moezt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 18a2 2 0 1 0 4 0a2 2 0 0 0-4 0m12 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0m2-6v-2a6 6 0 1 0-12 0v2M3 9l3 3l3-3");
}

</style>
