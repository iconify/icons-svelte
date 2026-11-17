<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-q59iq9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:stairs-fill" {...props}></Icon>
<style>
:global(.g-q59iq9r) {
  fill: currentColor;
  d: path("M6 16v-3a1 1 0 0 1 1-1h3V9a1 1 0 0 1 1-1h3V5a1 1 0 0 1 1-1h4a3 3 0 0 1 3 3v12a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3v-2a1 1 0 0 1 1-1Z");
}

</style>
