<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b21jgq7lu"/><path class="cr9qfdcye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-bedroom-child" {...props}></Icon>
<style>
:global(.b21jgq7lu) {
  fill: currentColor;
  d: path("M9 8.5h6v2H9zM7.51 12h9v2h-9z");
}

:global(.cr9qfdcye) {
  fill: currentColor;
  d: path("M22 2H2v20h20zm-4 15h-1.5v-1.5h-9V17H6v-6.32l1.5-.01V7h9v3.67H18z");
}

</style>
