<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="csrq8wbcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:stylus-outline-sharp" {...props}></Icon>
<style>
:global(.csrq8wbcn) {
  fill: currentColor;
  d: path("M8.95 20L2.7 21.3L4 15.05zm0 0L4 15.05L16.875 2.175l4.95 4.95zm-.3-2.525L19 7.125L16.875 5L6.525 15.35z");
}

</style>
