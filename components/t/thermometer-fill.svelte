<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="c9pallblo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:thermometer-fill" {...props}></Icon>
<style>
:global(.c9pallblo) {
  fill: currentColor;
  d: path("M212 56a28 28 0 1 0 28 28a28 28 0 0 0-28-28m0 40a12 12 0 1 1 12-12a12 12 0 0 1-12 12m-60 50.08V40a32 32 0 0 0-64 0v106.08a56 56 0 1 0 64 0M136 104h-32V40a16 16 0 0 1 32 0Z");
}

</style>
