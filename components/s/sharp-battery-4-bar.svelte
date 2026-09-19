<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r7enwu8kw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-battery-4-bar" {...props}></Icon>
<style>
:global(.r7enwu8kw) {
  fill: currentColor;
  d: path("M17 4v18H7V4h3V2h4v2zm-2 2H9v6h6z");
}

</style>
