<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xi8enmbzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:width-normal-sharp" {...props}></Icon>
<style>
:global(.xi8enmbzu) {
  fill: currentColor;
  d: path("M2 20V4h20v16zm2-2h4V6H4zm12 0h4V6h-4z");
}

</style>
