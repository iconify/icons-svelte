<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i5ombpb5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-east" {...props}></Icon>
<style>
:global(.i5ombpb5y) {
  fill: currentColor;
  d: path("m15 5l-1.41 1.41L18.17 11H2v2h16.17l-4.59 4.59L15 19l7-7z");
}

</style>
