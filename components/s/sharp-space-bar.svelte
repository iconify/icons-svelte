<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="klvgiqbuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-space-bar" {...props}></Icon>
<style>
:global(.klvgiqbuv) {
  fill: currentColor;
  d: path("M18 9v4H6V9H4v6h16V9z");
}

</style>
