<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmdd1xg6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-add-box" {...props}></Icon>
<style>
:global(.kmdd1xg6b) {
  fill: currentColor;
  d: path("M21 3H3v18h18zm-4 10h-4v4h-2v-4H7v-2h4V7h2v4h4z");
}

</style>
