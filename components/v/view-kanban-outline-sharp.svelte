<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n0xwgtbfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:view-kanban-outline-sharp" {...props}></Icon>
<style>
:global(.n0xwgtbfg) {
  fill: currentColor;
  d: path("M7.5 16.5h1v-9h-1zm4-5h1v-4h-1zm4 3h1v-7h-1zM4 20V4h16v16zm1-1h14V5H5zm0 0V5z");
}

</style>
