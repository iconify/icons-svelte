<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iw4ge6bvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:table-rows-narrow" {...props}></Icon>
<style>
:global(.iw4ge6bvv) {
  fill: currentColor;
  d: path("M3 15.5V13h18v2.5zM3 11V8.5h18V11zm0-4.5V4h18v2.5zM3 20v-2.5h18V20z");
}

</style>
