<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jvfkn81ff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:window-open-outline" {...props}></Icon>
<style>
:global(.jvfkn81ff) {
  fill: currentColor;
  d: path("M4 21V3h16v18zm2-10h5v-1h2v1h5V5H6zm0 8h12z");
}

</style>
