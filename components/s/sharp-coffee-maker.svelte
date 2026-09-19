<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qrg2dha4d"/><circle class="hedj3bbrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-coffee-maker" {...props}></Icon>
<style>
:global(.hedj3bbrm) {
  cx: 13px;
  cy: 9px;
  r: 1px;
  fill: currentColor;
}

:global(.qrg2dha4d) {
  fill: currentColor;
  d: path("M18 7V4h2V2H4v20h16v-2h-4.03A4.97 4.97 0 0 0 18 16v-5H8v5c0 1.64.81 3.09 2.03 4H6V4h2v3z");
}

</style>
