<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jo3g7fr_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-subscriptions" {...props}></Icon>
<style>
:global(.jo3g7fr_f) {
  fill: currentColor;
  d: path("M20 8H4V6h16zm-2-6H6v2h12zm4 8v12H2V10zm-6 6l-6-3.27v6.53z");
}

</style>
