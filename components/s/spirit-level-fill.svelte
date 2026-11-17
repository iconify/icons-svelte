<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ocv65522v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:spirit-level-fill" {...props}></Icon>
<style>
:global(.ocv65522v) {
  fill: currentColor;
  d: path("M5 6h14a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V9a3 3 0 0 1 3-3m3 4a1 1 0 0 0-2 0v4a1 1 0 0 0 2 0Zm8 0v4a1 1 0 0 0 2 0v-4a1 1 0 0 0-2 0m-5 4h2a2 2 0 1 0 0-4h-2a2 2 0 1 0 0 4");
}

</style>
