<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jfq5m4b5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:tv-displays-outline-sharp" {...props}></Icon>
<style>
:global(.jfq5m4b5k) {
  fill: currentColor;
  d: path("M3 15.327V3h14.27v1H4v11.327zM11.52 21v-2H6.77V6.77h15.25V19h-4.77v2zm-3.75-3h13.25V7.77H7.77zm6.634-5.116");
}

</style>
