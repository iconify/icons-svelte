<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vw45hdcdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:width-wide-outline-sharp" {...props}></Icon>
<style>
:global(.vw45hdcdl) {
  fill: currentColor;
  d: path("M2 20V4h20v16zm2-2h2V6H4zm4 0h8V6H8zm10 0h2V6h-2zM8 6v12z");
}

</style>
