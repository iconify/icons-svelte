<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q8zkrq46o"/><path class="ktj7_mbhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-signal-wifi-statusbar-connected-no-internet-4" {...props}></Icon>
<style>
:global(.ktj7_mbhl) {
  fill: currentColor;
  d: path("M12 4C7.31 4 3.07 5.9 0 8.98L12 21l5-5.01V8h5.92C19.97 5.51 16.16 4 12 4");
}

:global(.q8zkrq46o) {
  fill: currentColor;
  d: path("M19 18h2v2h-2zm0-8h2v6h-2z");
}

</style>
