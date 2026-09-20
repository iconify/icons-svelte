<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="gty2emb2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:sigma" {...props}></Icon>
<style>
:global(.gty2emb2m) {
  fill: currentColor;
  d: path("M184 72V56H80.65l53.6 67a8 8 0 0 1 0 10l-53.6 67H184v-16a8 8 0 0 1 16 0v24a8 8 0 0 1-8 8H64a8 8 0 0 1-6.25-13l60-75l-60-75A8 8 0 0 1 64 40h128a8 8 0 0 1 8 8v24a8 8 0 0 1-16 0");
}

</style>
