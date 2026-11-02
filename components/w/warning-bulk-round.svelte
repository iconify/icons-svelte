<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hlgb3ob_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:warning-bulk-round" {...props}></Icon>
<style>
:global(.hlgb3ob_q) {
  fill: currentColor;
  d: path("M13 14a1 1 0 0 1-2 0V6a1 1 0 0 1 2 0Zm-.99 3a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Z");
}

</style>
