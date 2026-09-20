<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vqhjvcjvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:transition-chop-sharp" {...props}></Icon>
<style>
:global(.vqhjvcjvu) {
  fill: currentColor;
  d: path("M2 20V4h20v16zm4.375-2H20V6h-4.325L18 15z");
}

</style>
