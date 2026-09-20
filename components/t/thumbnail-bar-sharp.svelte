<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="goajxdqhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:thumbnail-bar-sharp" {...props}></Icon>
<style>
:global(.goajxdqhb) {
  fill: currentColor;
  d: path("M2 20V4h6v16zm8 0V4h12v16z");
}

</style>
