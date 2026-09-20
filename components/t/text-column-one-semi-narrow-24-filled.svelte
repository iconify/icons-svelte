<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bxw4u9b5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-column-one-semi-narrow-24-filled" {...props}></Icon>
<style>
:global(.bxw4u9b5w) {
  fill: currentColor;
  d: path("M8 5a1 1 0 0 0 0 2h8a1 1 0 1 0 0-2zm0 4a1 1 0 0 0 0 2h8a1 1 0 1 0 0-2zm-1 5a1 1 0 0 1 1-1h8a1 1 0 1 1 0 2H8a1 1 0 0 1-1-1m1 3a1 1 0 1 0 0 2h8a1 1 0 1 0 0-2z");
}

</style>
