<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ov7q7vblz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-signal-cellular-no-sim" {...props}></Icon>
<style>
:global(.ov7q7vblz) {
  fill: currentColor;
  d: path("M19 3h-9L7.95 5.06L19 16.11zm-15.21.74L2.38 5.15L5 7.77V21h13.23l1.62 1.62l1.41-1.41z");
}

</style>
