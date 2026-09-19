<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dsogtngbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:yaata" {...props}></Icon>
<style>
:global(.dsogtngbm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39 9.512H9a2 2 0 0 0-2 2v26.976l6.977-6.976H39a2 2 0 0 0 2-2v-18a2 2 0 0 0-2-2m-3.056 11.102H12.056m13.028 5.767H12.056m23.888-11.533H12.056");
}

</style>
