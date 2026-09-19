<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ib-65u9jo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:veganradar" {...props}></Icon>
<style>
:global(.ib-65u9jo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 8.766L24 39.234L4.5 8.766h13.406L24 18.516l6.094-9.75");
}

</style>
