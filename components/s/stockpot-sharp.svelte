<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nimow2b_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:stockpot-sharp" {...props}></Icon>
<style>
:global(.nimow2b_z) {
  fill: currentColor;
  d: path("M3 20V8h18v12zM3 7V5h6V3h6v2h6v2z");
}

</style>
