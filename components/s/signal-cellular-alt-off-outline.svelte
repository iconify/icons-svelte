<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vhxra3bji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:signal-cellular-alt-off-outline" {...props}></Icon>
<style>
:global(.vhxra3bji) {
  fill: currentColor;
  d: path("M19.775 22.625L14 16.85V20h-3v-6.15L1.375 4.225L2.8 2.8l18.4 18.4zM20 17.15l-3-3V4h3zM5 20v-6h3v6z");
}

</style>
