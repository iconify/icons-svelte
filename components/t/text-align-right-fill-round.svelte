<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="en9t1ybbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:text-align-right-fill-round" {...props}></Icon>
<style>
:global(.en9t1ybbw) {
  fill: currentColor;
  d: path("M20 5a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2Zm0 4a1 1 0 0 1 0 2H10a1 1 0 0 1 0-2Zm0 4a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2Zm0 4a1 1 0 0 1 0 2H10a1 1 0 0 1 0-2Z");
}

</style>
