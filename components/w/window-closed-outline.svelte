<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iq73un8tz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:window-closed-outline" {...props}></Icon>
<style>
:global(.iq73un8tz) {
  fill: currentColor;
  d: path("M4 21V3h16v18zm2-10h5v-1h2v1h5V5H6zm0 8h12v-6H6zm0 0h12z");
}

</style>
