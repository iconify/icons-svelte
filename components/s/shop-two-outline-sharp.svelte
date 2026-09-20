<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s073occxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:shop-two-outline-sharp" {...props}></Icon>
<style>
:global(.s073occxk) {
  fill: currentColor;
  d: path("m12 15l5.5-3.5L12 8zM1 22V9h2v11h17v2zm4-4V5h5V1h8v4h5v13zm7-13h4V3h-4zM7 16h14V7H7zm0-9v9z");
}

</style>
