<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xnx4-7bft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-label" {...props}></Icon>
<style>
:global(.xnx4-7bft) {
  fill: currentColor;
  d: path("M17.03 5L3 5.01v13.98l14.03.01L22 12z");
}

</style>
