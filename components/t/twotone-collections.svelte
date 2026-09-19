<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i1e5go_1e"/><path class="gpfjqdbtz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-collections" {...props}></Icon>
<style>
:global(.gpfjqdbtz) {
  fill: currentColor;
  d: path("M8 2c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2zm12 14H8V4h12zm-4.33-5.17l-2.48 3.09l-1.69-2.25L9 15h10zM4 22h14v-2H4V6H2v14c0 1.1.9 2 2 2");
}

:global(.i1e5go_1e) {
  fill: currentColor;
  d: path("M8 16h12V4H8zm3.5-4.33l1.69 2.26l2.48-3.09L19 15H9z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
