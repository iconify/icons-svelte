<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jh9x8wbpo"/><circle class="xzditrbqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-fire-hydrant-alt" {...props}></Icon>
<style>
:global(.jh9x8wbpo) {
  fill: currentColor;
  d: path("M21 11h-3V8h2V6h-2.35a5.99 5.99 0 0 0-11.3 0H4v2h2v3H3v6h3v3H4v2h16v-2h-2v-3h3zm-9 6.5c-1.93 0-3.5-1.57-3.5-3.5s1.57-3.5 3.5-3.5s3.5 1.57 3.5 3.5s-1.57 3.5-3.5 3.5");
}

:global(.xzditrbqy) {
  cx: 12px;
  cy: 14px;
  r: 1.5px;
  fill: currentColor;
}

</style>
