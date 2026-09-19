<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lqvzfjbnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:thunder-vpn" {...props}></Icon>
<style>
:global(.lqvzfjbnk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.979 43.5l16.874-21.522H23.805l4.482-9.244h9.548L41.944 4.5H10.165l-4.109 8.234h12.983c-2.485 5.004-4.977 10.004-7.555 14.968l9.888-.067z");
}

</style>
