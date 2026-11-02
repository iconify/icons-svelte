<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qvvp9_b1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-chevron-double-left-fill-sharp" {...props}></Icon>
<style>
:global(.qvvp9_b1u) {
  fill: currentColor;
  d: path("M2 21V3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1m8.707-11.293a.999.999 0 1 0-1.414-1.414l-3 3a.997.997 0 0 0 0 1.414l3 3a.999.999 0 1 0 1.414-1.414L8.414 12Zm6 0a.999.999 0 1 0-1.414-1.414l-3 3a1 1 0 0 0 0 1.414l3 3a.999.999 0 1 0 1.414-1.414L14.414 12Z");
}

</style>
