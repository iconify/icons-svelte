<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="prtis2bxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:union-bold" {...props}></Icon>
<style>
:global(.prtis2bxt) {
  fill: currentColor;
  d: path("M212 64v80a84 84 0 0 1-168 0V64a12 12 0 0 1 24 0v80a60 60 0 0 0 120 0V64a12 12 0 0 1 24 0");
}

</style>
