<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="g_woxrbde"/><path class="nlm558pgq"/><path class="z5wetzsgo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:syphon" {...props}></Icon>
<style>
:global(.g_woxrbde) {
  d: path("M40.1 16.5v13.4c0 1.2-.6 2.3-1.7 2.9l-11.6 6.7M14 9.8L22.4 5c1-.6 2.3-.6 3.3 0l11.4 6.6M21.2 39.5L8.1 32");
}

:global(.nlm558pgq) {
  d: path("M32.8 28.9L25 33.4c-.6.4-1.4.4-2 0l-7.8-4.5c-.6-.4-1-1-1-1.8V18c0-.7.4-1.4 1-1.8l7.8-4.5c.6-.4 1.4-.4 2 0l7.8 4.5c.6.4 1 1 1 1.8v9.1c.1.7-.3 1.4-1 1.8");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.z5wetzsgo) {
  d: path("M7.9 13.5v30l13.3-2");
}

</style>
