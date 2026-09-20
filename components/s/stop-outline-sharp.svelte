<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rhf7l7mgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:stop-outline-sharp" {...props}></Icon>
<style>
:global(.rhf7l7mgl) {
  fill: currentColor;
  d: path("M8 8v8zM6 18V6h12v12zm2-2h8V8H8z");
}

</style>
