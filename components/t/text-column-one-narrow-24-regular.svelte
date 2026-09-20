<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="scd7tk8xw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-column-one-narrow-24-regular" {...props}></Icon>
<style>
:global(.scd7tk8xw) {
  fill: currentColor;
  d: path("M8.75 5a.75.75 0 0 0 0 1.5h6.5a.75.75 0 0 0 0-1.5zm0 4a.75.75 0 0 0 0 1.5h6.5a.75.75 0 0 0 0-1.5zM8 13.75a.75.75 0 0 1 .75-.75h6.5a.75.75 0 0 1 0 1.5h-6.5a.75.75 0 0 1-.75-.75M8.75 17a.75.75 0 0 0 0 1.5h6.5a.75.75 0 0 0 0-1.5z");
}

</style>
