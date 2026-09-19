<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kqdganb3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:tedit" {...props}></Icon>
<style>
:global(.kqdganb3y) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.909 4.5h25.837m-27.492 39l14.573-39M22.129 24h8.33M14.842 43.5h16.801");
}

</style>
