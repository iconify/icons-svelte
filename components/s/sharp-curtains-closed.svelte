<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l0vwpeb-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-curtains-closed" {...props}></Icon>
<style>
:global(.l0vwpeb-g) {
  fill: currentColor;
  d: path("M20 19V3H4v16H2v2h20v-2zM11 5h2v14h-2z");
}

</style>
