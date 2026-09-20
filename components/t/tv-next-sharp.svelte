<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qzfx6vtqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:tv-next-sharp" {...props}></Icon>
<style>
:global(.qzfx6vtqm) {
  fill: currentColor;
  d: path("M19.5 22.5L18 21l3-3l-3-3l1.5-1.5L24 18zM8 21v-2H2V3h20v9h-5v7h-2v2z");
}

</style>
