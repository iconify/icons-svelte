<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x9wn2abmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-battery-2-bar" {...props}></Icon>
<style>
:global(.x9wn2abmz) {
  fill: currentColor;
  d: path("M17 4v18H7V4h3V2h4v2zm-2 2H9v10h6z");
}

</style>
