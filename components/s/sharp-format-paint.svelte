<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zuepjb6mc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-format-paint" {...props}></Icon>
<style>
:global(.zuepjb6mc) {
  fill: currentColor;
  d: path("M18 4V2H4v6h14V6h1v4H9v12h4V12h8V4z");
}

</style>
