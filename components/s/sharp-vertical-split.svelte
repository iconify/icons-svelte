<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mht-6xb7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-vertical-split" {...props}></Icon>
<style>
:global(.mht-6xb7u) {
  fill: currentColor;
  d: path("M3 15h8v-2H3zm0 4h8v-2H3zm0-8h8V9H3zm0-6v2h8V5zm10 0h8v14h-8z");
}

</style>
