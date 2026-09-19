<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qs6wprbpf"/><path class="do-864bca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-change-history" {...props}></Icon>
<style>
:global(.do-864bca) {
  fill: currentColor;
  d: path("M12 4L2 20h20zm0 3.77L18.39 18H5.61z");
}

:global(.qs6wprbpf) {
  fill: currentColor;
  d: path("M12 7.77L5.61 18h12.78z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
