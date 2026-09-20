<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rh_qxd_ga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:tile-medium-sharp" {...props}></Icon>
<style>
:global(.rh_qxd_ga) {
  fill: currentColor;
  d: path("M3 19v-6h8v6zm10 0v-6h8v6zM3 11V5h18v6z");
}

</style>
