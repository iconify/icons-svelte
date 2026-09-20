<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="skr-doe8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:variables-outline-sharp" {...props}></Icon>
<style>
:global(.skr-doe8g) {
  fill: currentColor;
  d: path("M3 17V7h18v10zm2-2h14V9H5zm0 0V9z");
}

</style>
