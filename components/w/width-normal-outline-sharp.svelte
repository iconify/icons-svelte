<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o9u-49b7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:width-normal-outline-sharp" {...props}></Icon>
<style>
:global(.o9u-49b7w) {
  fill: currentColor;
  d: path("M2 20V4h20v16zm2-2h4V6H4zm6 0h4V6h-4zm6 0h4V6h-4zM10 6v12z");
}

</style>
