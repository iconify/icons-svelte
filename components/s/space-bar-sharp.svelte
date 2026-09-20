<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ozy0kubmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:space-bar-sharp" {...props}></Icon>
<style>
:global(.ozy0kubmi) {
  fill: currentColor;
  d: path("M4 15V9h2v4h12V9h2v6z");
}

</style>
