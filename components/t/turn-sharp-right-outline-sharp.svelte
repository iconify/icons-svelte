<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qg4llmb_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:turn-sharp-right-outline-sharp" {...props}></Icon>
<style>
:global(.qg4llmb_d) {
  fill: currentColor;
  d: path("M6 21v-8h10V6.8l-1.6 1.6L13 7l4-4l4 4l-1.4 1.4L18 6.8V15H8v6z");
}

</style>
