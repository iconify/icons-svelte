<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mjmpbxbtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:slice" {...props}></Icon>
<style>
:global(.mjmpbxbtu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 30.5a13 13 0 1 0-13-13h13Zm0 13a13 13 0 0 1-13-13h13Z");
}

</style>
