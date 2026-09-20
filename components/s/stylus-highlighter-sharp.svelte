<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="skts64d7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:stylus-highlighter-sharp" {...props}></Icon>
<style>
:global(.skts64d7v) {
  fill: currentColor;
  d: path("M7 16V3h2.475L17 6.725V16zm-3 5l1-3h14l1 3z");
}

</style>
