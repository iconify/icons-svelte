<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v2zu31-zx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:timer-10-sharp" {...props}></Icon>
<style>
:global(.v2zu31-zx) {
  fill: currentColor;
  d: path("M14 16h3V8h-3zm-3 3V5h9v14zm-5 0V8H4V5h5v14z");
}

</style>
