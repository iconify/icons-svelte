<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y6kb7nbgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:untis-mobile-alt" {...props}></Icon>
<style>
:global(.y6kb7nbgh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5c11.874 0 21.5 9.626 21.5 21.5S35.874 45.5 24 45.5S2.5 35.874 2.5 24C2.506 12.128 12.128 2.506 24 2.5m-.005 21.545h17.244M23.995 6.802v17.244m12.194-12.194L23.996 24.045");
}

</style>
