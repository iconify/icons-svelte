<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="gziwnon6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:union-thin" {...props}></Icon>
<style>
:global(.gziwnon6m) {
  fill: currentColor;
  d: path("M204 64v80a76 76 0 0 1-152 0V64a4 4 0 0 1 8 0v80a68 68 0 0 0 136 0V64a4 4 0 0 1 8 0");
}

</style>
