<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="er16v3lvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:view-cozy-sharp" {...props}></Icon>
<style>
:global(.er16v3lvg) {
  fill: currentColor;
  d: path("M4 10.5V4h6.5v6.5zM4 20v-6.5h6.5V20zm9.5-9.5V4H20v6.5zm0 9.5v-6.5H20V20z");
}

</style>
