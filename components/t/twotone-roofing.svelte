<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xmryzcccz"/><path class="qx66-bjff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-roofing" {...props}></Icon>
<style>
:global(.qx66-bjff) {
  fill: currentColor;
  d: path("M13 18h-2v-2h2zm2-4H9v6h6zm4-4.7V4h-3v2.6L12 3L2 12h3l7-6.31L19 12h3z");
}

:global(.xmryzcccz) {
  fill: currentColor;
  d: path("M11 16h2v2h-2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
