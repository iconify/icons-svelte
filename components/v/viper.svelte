<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s_2lkdd9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:viper" {...props}></Icon>
<style>
:global(.s_2lkdd9j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.22 42.26L5.5 5.74h13.9l9.15 17.85l8.38-17.75h5.57Zm4.33-18.67l2.55 4.96");
}

</style>
