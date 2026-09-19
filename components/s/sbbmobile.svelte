<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rb-vgcpoj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:sbbmobile" {...props}></Icon>
<style>
:global(.rb-vgcpoj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.76 14.25L43.5 24l-9.75 9.75m-19.51 0L4.5 24l9.75-9.75M4.5 24h39M24 14.25v19.5");
}

</style>
