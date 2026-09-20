<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yo9pnmbhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:window-open" {...props}></Icon>
<style>
:global(.yo9pnmbhf) {
  fill: currentColor;
  d: path("M4 21V3h16v18zm3-10h4v-1h2v1h4V6H7zm-1 8h12V5H6z");
}

</style>
