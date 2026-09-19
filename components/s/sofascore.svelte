<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h6wye8_9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:sofascore" {...props}></Icon>
<style>
:global(.h6wye8_9i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.532 5.5h-37v18.347h9.047v-9.402h27.953zm-37 37h37V24.153h-9.047v9.402H5.532z");
}

</style>
