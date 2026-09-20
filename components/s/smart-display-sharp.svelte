<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="velbbw06e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:smart-display-sharp" {...props}></Icon>
<style>
:global(.velbbw06e) {
  fill: currentColor;
  d: path("m9.5 16.5l7-4.5l-7-4.5zM2 20V4h20v16z");
}

</style>
