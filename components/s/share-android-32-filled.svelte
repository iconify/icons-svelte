<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nwfoefbtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:share-android-32-filled" {...props}></Icon>
<style>
:global(.nwfoefbtd) {
  fill: currentColor;
  d: path("M20 7.5q.001.553.128 1.068l-9.15 4.575a4.5 4.5 0 1 0 0 5.713l9.15 4.576Q20 23.947 20 24.5a4.5 4.5 0 1 0 1.023-2.857l-9.15-4.575a4.5 4.5 0 0 0 0-2.136l9.15-4.575A4.5 4.5 0 1 0 20 7.5");
}

</style>
