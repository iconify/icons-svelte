<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ayh04l5-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-water-damage" {...props}></Icon>
<style>
:global(.ayh04l5-a) {
  fill: currentColor;
  d: path("M12 3L2 12h3v8h14v-8h3zm0 13c-1.1 0-2-.9-2-2s2-4 2-4s2 2.9 2 4s-.9 2-2 2");
}

</style>
