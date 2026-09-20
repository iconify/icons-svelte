<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ydc3gto7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:split-scene-sharp" {...props}></Icon>
<style>
:global(.ydc3gto7h) {
  fill: currentColor;
  d: path("M3 20V4h6v16zm8 2V2h2v2h8v16h-8v2z");
}

</style>
