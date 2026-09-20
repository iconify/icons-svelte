<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fnxy45bka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-hanging-24-regular" {...props}></Icon>
<style>
:global(.fnxy45bka) {
  fill: currentColor;
  d: path("M2.75 5a.75.75 0 0 0 0 1.5h18.5a.75.75 0 0 0 0-1.5zm7 13a.75.75 0 0 0 0 1.5h11.5a.75.75 0 0 0 0-1.5zM9 12.25a.75.75 0 0 1 .75-.75h11.5a.75.75 0 0 1 0 1.5H9.75a.75.75 0 0 1-.75-.75m-5.22.72a.75.75 0 0 0-1.06 1.06l1.47 1.47l-1.47 1.47a.75.75 0 1 0 1.06 1.06l2-2a.75.75 0 0 0 0-1.06z");
}

</style>
