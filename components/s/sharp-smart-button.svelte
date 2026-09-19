<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dgwrkci2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-smart-button" {...props}></Icon>
<style>
:global(.dgwrkci2h) {
  fill: currentColor;
  d: path("M22 17h-3v-2h1V9H4v6h6v2H2V7h20zm-7.5 2l1.09-2.41L18 15.5l-2.41-1.09L14.5 12l-1.09 2.41L11 15.5l2.41 1.09zm2.5-5l.62-1.38L19 12l-1.38-.62L17 10l-.62 1.38L15 12l1.38.62z");
}

</style>
