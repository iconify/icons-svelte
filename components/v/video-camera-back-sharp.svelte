<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r4dn2jb5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:video-camera-back-sharp" {...props}></Icon>
<style>
:global(.r4dn2jb5k) {
  fill: currentColor;
  d: path("M5 16h10l-3.45-4.5l-2.3 3l-1.55-2zm-3 4V4h16v6.5l4-4v11l-4-4V20z");
}

</style>
