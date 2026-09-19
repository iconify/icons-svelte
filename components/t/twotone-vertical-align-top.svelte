<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i2y-9b59z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-vertical-align-top" {...props}></Icon>
<style>
:global(.i2y-9b59z) {
  fill: currentColor;
  d: path("M4 3h16v2H4zm4 8h3v10h2V11h3l-4-4z");
}

</style>
