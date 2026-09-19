<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_qgrr0lu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-sim-card-download" {...props}></Icon>
<style>
:global(.h_qgrr0lu) {
  fill: currentColor;
  d: path("M20 2H10L4 8v14h16zm-8 15l-4-4h3V9.02L13 9v4h3z");
}

</style>
