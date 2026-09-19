<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="grh3wh9rs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-free-breakfast" {...props}></Icon>
<style>
:global(.grh3wh9rs) {
  fill: currentColor;
  d: path("M20 3H4v14h14v-7h2a2 2 0 0 0 2-2V5c0-1.1-.9-2-2-2m0 5h-2V5h2zM4 19h16v2H4z");
}

</style>
