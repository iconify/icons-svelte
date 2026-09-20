<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tbjin1bwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:stack-off-sharp" {...props}></Icon>
<style>
:global(.tbjin1bwl) {
  fill: currentColor;
  d: path("M22 19.15L10.85 8H22zM14 6V4H6.85l-2-2H16v4zm6.575 17.425L19.15 22H8V10.85l-4-4V14h2v2H2V4.85L.575 3.425L2 2l20 20z");
}

</style>
