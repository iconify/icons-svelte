<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r82yh1xlb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:wallet-fill" {...props}></Icon>
<style>
:global(.r82yh1xlb) {
  fill: currentColor;
  d: path("M22 6v2h-5a3 3 0 0 0-3 3v2a3 3 0 0 0 3 3h5v2a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3m-5 8a.997.997 0 0 1-1-1v-2a.997.997 0 0 1 1-1h5v4Zm1-3a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Z");
}

</style>
