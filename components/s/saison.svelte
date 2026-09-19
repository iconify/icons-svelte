<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nfbwn4bly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:saison" {...props}></Icon>
<style>
:global(.nfbwn4bly) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.692 34.743C40.966 32.344 38.662 20.16 24 4.5C9.338 20.16 7.034 32.344 22.307 34.743L24 9.329zm0 0V43.5h-3.385v-8.757z");
}

</style>
