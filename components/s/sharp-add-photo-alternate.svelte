<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x4th41tiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-add-photo-alternate" {...props}></Icon>
<style>
:global(.x4th41tiw) {
  fill: currentColor;
  d: path("M19 7v2.99s-1.99.01-2 0V7h-3s.01-1.99 0-2h3V2h2v3h3v2zm-3 4V8h-3V5H3v16h16V11zM5 19l3-4l2 3l3-4l4 5z");
}

</style>
