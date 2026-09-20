<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pmo7cdbgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:ungroup-outline" {...props}></Icon>
<style>
:global(.pmo7cdbgc) {
  fill: currentColor;
  d: path("m8.7 16.7l-1.4-1.4l4.3-4.3H8V9h7v7h-2v-3.6zM19 12V5h-7V3h9v9zM5 21q-.825 0-1.412-.587T3 19V3h2v16h16v2z");
}

</style>
