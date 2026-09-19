<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kdb7kshkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:tydom" {...props}></Icon>
<style>
:global(.kdb7kshkv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 42.5v-37M24 24H5.5m0 0L24 42.5m10.5-37h-25a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h25a8 8 0 0 0 8-8v-21a8 8 0 0 0-8-8");
}

</style>
