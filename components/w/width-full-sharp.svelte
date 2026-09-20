<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nzh7dfb0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:width-full-sharp" {...props}></Icon>
<style>
:global(.nzh7dfb0m) {
  fill: currentColor;
  d: path("M2 20V4h20v16zm2-2h1V6H4zm15 0h1V6h-1z");
}

</style>
