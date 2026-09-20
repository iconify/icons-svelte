<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wiwd-8b5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:view-kanban-sharp" {...props}></Icon>
<style>
:global(.wiwd-8b5c) {
  fill: currentColor;
  d: path("M7 17h2V7H7zm4-5h2V7h-2zm4 3h2V7h-2zM3 21V3h18v18z");
}

</style>
