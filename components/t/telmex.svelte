<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cs1n8lbgm"/><path class="hwftn4b8i"/><path class="fttck0yws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:telmex" {...props}></Icon>
<style>
:global(.cs1n8lbgm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.53 18.77L4.5 34.176h7.024l3.455-6.502L24 34.356");
}

:global(.fttck0yws) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.47 18.77l8.03 15.406h-7.024l-3.455-6.502L24 34.356");
}

:global(.hwftn4b8i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.945 27.085V18.77h7.525l.772 1.481h6.764v-6.607H4.994v6.607h6.764l.772-1.481h7.525v8.315z");
}

</style>
