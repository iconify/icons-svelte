<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rfasldhko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:slideshow-sharp" {...props}></Icon>
<style>
:global(.rfasldhko) {
  fill: currentColor;
  d: path("m9.5 16.5l7-4.5l-7-4.5zM3 21V3h18v18z");
}

</style>
