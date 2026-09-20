<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cvs2pbbvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:tag-circle-20-filled" {...props}></Icon>
<style>
:global(.cvs2pbbvd) {
  fill: currentColor;
  d: path("M2 10a8 8 0 1 1 16 0a8 8 0 0 1-16 0m4-1.5v3A1.5 1.5 0 0 0 7.5 13h4.058c.4 0 .789-.137 1.1-.39l1.786-1.444a1.5 1.5 0 0 0 0-2.332L12.658 7.39a1.75 1.75 0 0 0-1.1-.39H7.5A1.5 1.5 0 0 0 6 8.5");
}

</style>
