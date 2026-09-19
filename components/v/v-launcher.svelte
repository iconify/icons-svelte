<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fr6fnfb6i"/><path class="yui2dwdmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:v-launcher" {...props}></Icon>
<style>
:global(.fr6fnfb6i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m7.12 4.5l15.872 35.926M24 43.5l15.519-11.136L40.88 4.5L24 14.93L7.12 4.5l1.361 27.864z");
}

:global(.yui2dwdmw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.889 24.795L24 43.5L8.111 23.596m18.483 16.83h-5.048M40.88 4.5L25.008 40.426M24 14.93L8.111 23.596m31.778 1.199L24 14.93");
}

</style>
