<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xdj9f9utq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:video-fill-sharp" {...props}></Icon>
<style>
:global(.xdj9f9utq) {
  fill: currentColor;
  d: path("M2 18V6a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v2.382l4.553-2.276A1 1 0 0 1 22 7v10a1 1 0 0 1-1.447.894L16 15.618V18a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1m14-4.618l4 2V8.618l-4 2Z");
}

</style>
