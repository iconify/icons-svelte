<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="rpxe9ibnu"/><path class="xi7mcbcba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-priority-high" {...props}></Icon>
<style>
:global(.rpxe9ibnu) {
  cx: 12px;
  cy: 19px;
  r: 2px;
  fill: currentColor;
}

:global(.xi7mcbcba) {
  fill: currentColor;
  d: path("M10 3h4v12h-4z");
}

</style>
