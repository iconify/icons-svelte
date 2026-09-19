<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e0xw4_bwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-text-fields" {...props}></Icon>
<style>
:global(.e0xw4_bwl) {
  fill: currentColor;
  d: path("M12.5 12h3v7h3v-7h3V9h-9zm3-8h-13v3h5v12h3V7h5z");
}

</style>
