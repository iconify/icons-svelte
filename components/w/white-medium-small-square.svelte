<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="t7zzz4baa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noto-v1:white-medium-small-square" {...props}></Icon>
<style>
:global(.t7zzz4baa) {
  fill: var(--svg-color--e0e0e0, #e0e0e0);
  d: path("M40.03 40.03h47.95v47.95H40.03z");
}

</style>
