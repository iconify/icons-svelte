<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xlixpg-ec"/><circle class="yfz3w9lrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-woman-2" {...props}></Icon>
<style>
:global(.xlixpg-ec) {
  fill: currentColor;
  d: path("M13.41 7h-2.82L7 16h3.5v6h3v-6H17z");
}

:global(.yfz3w9lrl) {
  cx: 12px;
  cy: 4px;
  r: 2px;
  fill: currentColor;
}

</style>
