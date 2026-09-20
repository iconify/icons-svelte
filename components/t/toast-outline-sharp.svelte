<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="az8j-mbjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:toast-outline-sharp" {...props}></Icon>
<style>
:global(.az8j-mbjx) {
  fill: currentColor;
  d: path("M6 18h12v-2H6zm-3 3V3h18v18zm2-2h14V5H5zm0 0V5z");
}

</style>
