<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g_vswpb3u"/><path class="mf1yjdbqf"/><path class="tri553iuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:welab-bank" {...props}></Icon>
<style>
:global(.g_vswpb3u) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 12.3h7.8v7.8H4.5z");
}

:global(.mf1yjdbqf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.1 12.375L4.5 27.825v7.95h7.8l15.6-15.6v-7.8z");
}

:global(.tri553iuo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.7 12.45L20.1 27.9v7.95h7.8l15.6-15.6v-7.8z");
}

</style>
