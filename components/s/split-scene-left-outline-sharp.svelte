<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x9igppb4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:split-scene-left-outline-sharp" {...props}></Icon>
<style>
:global(.x9igppb4g) {
  fill: currentColor;
  d: path("M14.885 19v-1H19V6h-4.115V5H20v14zM11.5 21v-2H4V5h7.5V3h1v18zM19 6v12z");
}

</style>
