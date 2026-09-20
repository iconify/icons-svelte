<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="kcbfxab_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:split-horizontal-28-filled" {...props}></Icon>
<style>
:global(.kcbfxab_n) {
  fill: currentColor;
  d: path("M2.75 12.998a.75.75 0 0 0 0 1.5h22.5a.75.75 0 0 0 0-1.5zM21.25 2A2.75 2.75 0 0 1 24 4.75v7.248H4V4.75A2.75 2.75 0 0 1 6.75 2zM4 22.75v-7.252h20v7.252a2.75 2.75 0 0 1-2.75 2.75H6.75A2.75 2.75 0 0 1 4 22.75");
}

</style>
