<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jq4h06tun"/><path class="yh463abyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:stayfree" {...props}></Icon>
<style>
:global(.jq4h06tun) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 23.946a21.497 21.497 0 1 1-.001-.173");
}

:global(.yh463abyc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.53 21.994l5.827 4.91l10.027-8.81");
}

</style>
