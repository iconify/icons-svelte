<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ejsolib7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-maximize" {...props}></Icon>
<style>
:global(.ejsolib7l) {
  fill: currentColor;
  d: path("M3 3h18v2H3z");
}

</style>
