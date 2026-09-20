<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="bpggxmdmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:superset-proper-of" {...props}></Icon>
<style>
:global(.bpggxmdmw) {
  fill: currentColor;
  d: path("M224 128a88.1 88.1 0 0 1-88 88H64a8 8 0 0 1 0-16h72a72 72 0 0 0 0-144H64a8 8 0 0 1 0-16h72a88.1 88.1 0 0 1 88 88");
}

</style>
