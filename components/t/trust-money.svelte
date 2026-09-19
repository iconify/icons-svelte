<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i1qzd0rhx"/><ellipse class="ymlr7lnsx"/><ellipse class="zsd-wtb6j"/><path class="us7kfgbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:trust-money" {...props}></Icon>
<style>
:global(.i1qzd0rhx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.737 22.415L19.08 32.79c-.566 1.037-.252 1.729.786 1.729h.518m.942-9.337h3.804");
}

:global(.us7kfgbeo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.347 15.002h5.124V42.5H9.893v-9.197");
}

:global(.ymlr7lnsx) {
  cx: 22.242px;
  cy: 27.737px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 11.052px;
  ry: 10.985px;
}

:global(.zsd-wtb6j) {
  cx: 22.242px;
  cy: 22.111px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 16.713px;
  ry: 16.611px;
}

</style>
