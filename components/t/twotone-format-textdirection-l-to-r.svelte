<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="caxvf9y_w"/><path class="o4igdjb0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-format-textdirection-l-to-r" {...props}></Icon>
<style>
:global(.caxvf9y_w) {
  fill: currentColor;
  d: path("M9 8V4c-1.1 0-2 .9-2 2s.9 2 2 2");
  opacity: var(--svg-opacity--0-3, 0.3);
}

:global(.o4igdjb0e) {
  fill: currentColor;
  d: path("M9 10v5h2V4h2v11h2V4h2V2H9C6.79 2 5 3.79 5 6s1.79 4 4 4m0-6v4c-1.1 0-2-.9-2-2s.9-2 2-2m12 14l-4-4v3H5v2h12v3z");
}

</style>
