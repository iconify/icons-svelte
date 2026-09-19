<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ln9wfbmoi"/><path class="psdx19bvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-eject" {...props}></Icon>
<style>
:global(.ln9wfbmoi) {
  fill: currentColor;
  d: path("M12 8.6L9.07 13h5.86z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

:global(.psdx19bvf) {
  fill: currentColor;
  d: path("M5 17h14v2H5zm7-12L5.33 15h13.34zm0 3.6l2.93 4.4H9.07z");
}

</style>
