<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wal714huu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:video-camera-back-outline-sharp" {...props}></Icon>
<style>
:global(.wal714huu) {
  fill: currentColor;
  d: path("M2 20V4h16v6.5l4-4v11l-4-4V20zm2-2h12V6H4zm0 0V6zm1-2h10l-3.45-4.5l-2.3 3l-1.55-2z");
}

</style>
