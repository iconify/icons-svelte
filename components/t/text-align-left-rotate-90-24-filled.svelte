<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="te1i-z8gp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-align-left-rotate-90-24-filled" {...props}></Icon>
<style>
:global(.te1i-z8gp) {
  fill: currentColor;
  d: path("M18 2a1 1 0 0 1 1 1v15a1 1 0 1 1-2 0V3a1 1 0 0 1 1-1M6 2a1 1 0 0 1 1 1v11a1 1 0 1 1-2 0V3a1 1 0 0 1 1-1m7 1a1 1 0 1 0-2 0v18a1 1 0 1 0 2 0z");
}

</style>
