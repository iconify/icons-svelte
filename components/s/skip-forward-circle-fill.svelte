<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="uh-e9eb_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:skip-forward-circle-fill" {...props}></Icon>
<style>
:global(.uh-e9eb_w) {
  fill: currentColor;
  d: path("M128 24a104 104 0 1 0 104 104A104.11 104.11 0 0 0 128 24m40 144a8 8 0 0 1-16 0v-30.17l-51.35 36.68A8 8 0 0 1 88 168V88a8 8 0 0 1 12.65-6.51L152 118.17V88a8 8 0 0 1 16 0Z");
}

</style>
