<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="sx_947k2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:vinyl-record-light" {...props}></Icon>
<style>
:global(.sx_947k2k) {
  fill: currentColor;
  d: path("M128 26a102 102 0 1 0 102 102A102.12 102.12 0 0 0 128 26m0 192a90 90 0 1 1 90-90a90.1 90.1 0 0 1-90 90m0-148a58.07 58.07 0 0 0-58 58a6 6 0 0 1-12 0a70.08 70.08 0 0 1 70-70a6 6 0 0 1 0 12m70 58a70.08 70.08 0 0 1-70 70a6 6 0 0 1 0-12a58.07 58.07 0 0 0 58-58a6 6 0 0 1 12 0m-40 0a30 30 0 1 0-30 30a30 30 0 0 0 30-30m-48 0a18 18 0 1 1 18 18a18 18 0 0 1-18-18");
}

</style>
