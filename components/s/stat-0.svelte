<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f2bnb9bzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:stat-0" {...props}></Icon>
<style>
:global(.f2bnb9bzw) {
  fill: currentColor;
  d: path("m12 19l-7-7l7-7l7 7z");
}

</style>
