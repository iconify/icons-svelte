<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="er4pp33zl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:web-asset-16-filled" {...props}></Icon>
<style>
:global(.er4pp33zl) {
  fill: currentColor;
  d: path("M4.5 2A2.5 2.5 0 0 0 2 4.5v7A2.5 2.5 0 0 0 4.5 14h7a2.5 2.5 0 0 0 2.5-2.5v-7A2.5 2.5 0 0 0 11.5 2zM5 5h6a.5.5 0 0 1 0 1H5a.5.5 0 0 1 0-1");
}

</style>
