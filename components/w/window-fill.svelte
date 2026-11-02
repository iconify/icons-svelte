<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ftqvu8bsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:window-fill" {...props}></Icon>
<style>
:global(.ftqvu8bsq) {
  fill: currentColor;
  d: path("M22 18a3 3 0 0 1-3 3H5a3.004 3.004 0 0 1-3-3V6a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3ZM4 18a1 1 0 0 0 1 1h14a1 1 0 0 0 1-1V9H4Z");
}

</style>
