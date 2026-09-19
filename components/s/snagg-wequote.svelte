<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kdkpahbgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:snagg-wequote" {...props}></Icon>
<style>
:global(.kdkpahbgm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 2.5l18.62 10.75v21.5L24 45.5L5.38 34.75v-21.5zm18.618 17.915L11.585 38.332");
}

</style>
