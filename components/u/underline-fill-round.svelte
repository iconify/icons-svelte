<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wk7cx-bnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:underline-fill-round" {...props}></Icon>
<style>
:global(.wk7cx-bnj) {
  fill: currentColor;
  d: path("M9 5v6a3 3 0 1 0 6 0V5a1 1 0 0 1 2 0v6a5 5 0 0 1-10 0V5a1 1 0 0 1 2 0m9 13a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2Z");
}

</style>
