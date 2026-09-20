<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lkpuntb9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:table-rows" {...props}></Icon>
<style>
:global(.lkpuntb9t) {
  fill: currentColor;
  d: path("M20 20H4v-4.592h16zm0-5.592H4V9.587h16zm0-5.821H4V4h16z");
}

</style>
