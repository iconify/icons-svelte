<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c31shfbcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-warning-fill" {...props}></Icon>
<style>
:global(.c31shfbcm) {
  fill: currentColor;
  d: path("M2 5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm11 3a1 1 0 0 0-2 0v5a1 1 0 0 0 2 0Zm-1 7a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Z");
}

</style>
