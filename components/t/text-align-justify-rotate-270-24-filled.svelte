<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="myq5uypaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-align-justify-rotate-270-24-filled" {...props}></Icon>
<style>
:global(.myq5uypaj) {
  fill: currentColor;
  d: path("M6 22a1 1 0 0 1-1-1V3a1 1 0 0 1 2 0v18a1 1 0 0 1-1 1m12 0a1 1 0 0 1-1-1V3a1 1 0 1 1 2 0v18a1 1 0 0 1-1 1m-7-1a1 1 0 1 0 2 0V3a1 1 0 1 0-2 0z");
}

</style>
