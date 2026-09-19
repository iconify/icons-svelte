<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xdgjoqb7q"/><path class="ct2iyebsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-network-wifi-3-bar" {...props}></Icon>
<style>
:global(.ct2iyebsd) {
  fill: currentColor;
  d: path("M12 4C7.31 4 3.07 5.9 0 8.98L12 21L24 8.98A16.88 16.88 0 0 0 12 4M2.92 9.07C5.51 7.08 8.67 6 12 6s6.49 1.08 9.08 3.07l-2.85 2.86A10.95 10.95 0 0 0 12 10c-2.31 0-4.46.71-6.23 1.93z");
}

:global(.xdgjoqb7q) {
  fill: currentColor;
  d: path("M2.92 9.07C5.51 7.08 8.67 6 12 6s6.49 1.08 9.08 3.07l-2.85 2.86A10.95 10.95 0 0 0 12 10c-2.31 0-4.46.71-6.23 1.93z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
