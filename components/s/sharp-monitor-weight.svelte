<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ec8llxlgh"/><path class="hnpre0bff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-monitor-weight" {...props}></Icon>
<style>
:global(.ec8llxlgh) {
  fill: currentColor;
  d: path("M21 3H3v18h18zm-6.8 8.2c-3.23 2.43-6.84-1.18-4.4-4.41c3.23-2.42 6.83 1.19 4.4 4.41");
}

:global(.hnpre0bff) {
  fill: currentColor;
  d: path("M10 8.5h1v1h-1zm1.5 0h1v1h-1zm1.5 0h1v1h-1z");
}

</style>
