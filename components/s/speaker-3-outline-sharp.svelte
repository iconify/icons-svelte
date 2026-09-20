<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zc0s-qbln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:speaker-3-outline-sharp" {...props}></Icon>
<style>
:global(.zc0s-qbln) {
  fill: currentColor;
  d: path("M6 19h12V4H6zm2 3v-1H4V2h16v19h-4v1zm4-10.5");
}

</style>
