<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j5ttez39r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:smbc" {...props}></Icon>
<style>
:global(.j5ttez39r) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11 43.5l8.5-4l9-12l8.5-4v-19l-8.5 4l-9 12l-8.5 4zm8.5-23v19m9-31v19");
}

</style>
