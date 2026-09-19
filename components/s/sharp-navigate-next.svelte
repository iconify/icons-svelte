<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jsxicibnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-navigate-next" {...props}></Icon>
<style>
:global(.jsxicibnj) {
  fill: currentColor;
  d: path("M10.02 6L8.61 7.41L13.19 12l-4.58 4.59L10.02 18l6-6z");
}

</style>
