<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ace361ucv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:stylus-highlighter-outline-sharp" {...props}></Icon>
<style>
:global(.ace361ucv) {
  fill: currentColor;
  d: path("M7 16V3h2.475L17 6.725V16zm2-2h6V7.975L9 5zm-5 7l1-3h14l1 3zm5-7h6z");
}

</style>
