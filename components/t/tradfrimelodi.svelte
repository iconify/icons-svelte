<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dlf8lebna"/><g class="y9tr6bcfx"><circle class="z73jwbbls"/><path class="tqw97ibps"/></g><g class="y9tr6bcfx"><circle class="nvn715voe"/><path class="uzx-xxkcd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:tradfrimelodi" {...props}></Icon>
<style>
:global(.dlf8lebna) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.935 43.5h14.13M24 14.808V43.5m5.047-39H18.953l-5 10.308h20.094z");
}

:global(.nvn715voe) {
  cx: 18.658px;
  cy: 26.951px;
  r: 1.723px;
}

:global(.tqw97ibps) {
  d: path("m33 26.907l-3.224.686l2.017 8.631");
}

:global(.uzx-xxkcd) {
  d: path("m21.067 21.054l-1.924.41l1.203 5.149");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.z73jwbbls) {
  cx: 28.963px;
  cy: 36.79px;
  r: 2.888px;
}

</style>
