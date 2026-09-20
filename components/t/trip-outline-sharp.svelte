<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qixyqcb4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:trip-outline-sharp" {...props}></Icon>
<style>
:global(.qixyqcb4q) {
  fill: currentColor;
  d: path("M2 21V6h6V2h8v4h6v15zm8-15h4V4h-4zM6 8H4v11h2zm10 11V8H8v11zm2-11v11h2V8zm-6 5.5");
}

</style>
