<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ir-d8yxvf"/><path class="t3803is0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-vertical-split" {...props}></Icon>
<style>
:global(.ir-d8yxvf) {
  fill: currentColor;
  d: path("M15 7h4v10h-4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

:global(.t3803is0m) {
  fill: currentColor;
  d: path("M3 13h8v2H3zm0 4h8v2H3zm0-8h8v2H3zm0-4h8v2H3zm10 0v14h8V5zm6 12h-4V7h4z");
}

</style>
