<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lvsgf9bmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-3k" {...props}></Icon>
<style>
:global(.lvsgf9bmf) {
  fill: currentColor;
  d: path("M21 3H3v18h18zM11 9v6H6.5v-1.5h3v-1h-2v-1h2v-1h-3V9zm7 6h-1.75l-1.75-2.25V15H13V9h1.5v2.25L16.25 9H18l-2.25 3z");
}

</style>
