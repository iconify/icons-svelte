<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uv1to912d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-column-one-semi-narrow-24-regular" {...props}></Icon>
<style>
:global(.uv1to912d) {
  fill: currentColor;
  d: path("M7.75 5a.75.75 0 0 0 0 1.5h8.5a.75.75 0 0 0 0-1.5zm0 4a.75.75 0 0 0 0 1.5h8.5a.75.75 0 0 0 0-1.5zM7 13.75a.75.75 0 0 1 .75-.75h8.5a.75.75 0 0 1 0 1.5h-8.5a.75.75 0 0 1-.75-.75M7.75 17a.75.75 0 0 0 0 1.5h8.5a.75.75 0 0 0 0-1.5z");
}

</style>
