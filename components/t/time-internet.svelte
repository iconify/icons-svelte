<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p9zmp2bcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:time-internet" {...props}></Icon>
<style>
:global(.p9zmp2bcv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.611 5.5v27.13c0 5.45 4.42 9.87 9.87 9.87s9.87-4.42 9.87-9.87v-6.066m3.144-18.812l-30.99 9.76");
}

</style>
