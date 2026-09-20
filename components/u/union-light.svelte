<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="i9g9dibsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:union-light" {...props}></Icon>
<style>
:global(.i9g9dibsl) {
  fill: currentColor;
  d: path("M206 64v80a78 78 0 0 1-156 0V64a6 6 0 0 1 12 0v80a66 66 0 0 0 132 0V64a6 6 0 0 1 12 0");
}

</style>
