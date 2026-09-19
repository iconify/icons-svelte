<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kouzhzbkd"/><circle class="yfz3w9lrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-woman-2" {...props}></Icon>
<style>
:global(.kouzhzbkd) {
  fill: currentColor;
  d: path("M13.94 8.31C13.62 7.52 12.85 7 12 7s-1.62.52-1.94 1.31L7 16h3.5v6h3v-6H17z");
}

:global(.yfz3w9lrl) {
  cx: 12px;
  cy: 4px;
  r: 2px;
  fill: currentColor;
}

</style>
