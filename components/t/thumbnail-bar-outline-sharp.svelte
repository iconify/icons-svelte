<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bu3e3bbkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:thumbnail-bar-outline-sharp" {...props}></Icon>
<style>
:global(.bu3e3bbkv) {
  fill: currentColor;
  d: path("M2 20V4h20v16zm8-2h10V6H10zm-2 0V6H4v12zm-4 0V6zm4 0h2zM8 6h2z");
}

</style>
