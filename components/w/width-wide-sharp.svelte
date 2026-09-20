<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u2ju54d9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:width-wide-sharp" {...props}></Icon>
<style>
:global(.u2ju54d9g) {
  fill: currentColor;
  d: path("M2 20V4h20v16zm2-2h2V6H4zm14 0h2V6h-2z");
}

</style>
