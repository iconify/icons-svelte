<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s90hfmbru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:word-maker" {...props}></Icon>
<style>
:global(.s90hfmbru) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 17.833h12.333v12.333H5.5zm12.333 0h12.333v12.333H17.833zm0 12.334h12.333V42.5H17.833zm12.334-12.334H42.5v12.333H30.167zm0-12.333H42.5v12.333H30.167z");
}

</style>
