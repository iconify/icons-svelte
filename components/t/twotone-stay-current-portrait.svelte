<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tr9vo_7ko"/><path class="kfjsdhbyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-stay-current-portrait" {...props}></Icon>
<style>
:global(.kfjsdhbyk) {
  fill: currentColor;
  d: path("M17 1.01L7 1c-1.1 0-1.99.9-1.99 2v18c0 1.1.89 2 1.99 2h10c1.1 0 2-.9 2-2V3c0-1.1-.9-1.99-2-1.99M17 19H7V5h10z");
}

:global(.tr9vo_7ko) {
  fill: currentColor;
  d: path("M7 5h10v14H7z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
