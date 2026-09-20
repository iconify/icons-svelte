<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r8ne-k42k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:subdirectory-arrow-left" {...props}></Icon>
<style>
:global(.r8ne-k42k) {
  fill: currentColor;
  d: path("m10 21l-6-6l6.025-6.025l1.4 1.425l-3.6 3.6H17V4h2v12H7.825l3.6 3.575z");
}

</style>
