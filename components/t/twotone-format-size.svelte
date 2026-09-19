<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e1c1fvm9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-format-size" {...props}></Icon>
<style>
:global(.e1c1fvm9g) {
  fill: currentColor;
  d: path("M3 12h3v7h3v-7h3V9H3zm6-5h5v12h3V7h5V4H9z");
}

</style>
