<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bebas-jyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:taskmanager" {...props}></Icon>
<style>
:global(.bebas-jyr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.69 26.88h7.81v15.147h-7.81zM20.414 5.973h6.942v36.054h-6.942zM5.5 17.28h7.352v24.747H5.5z");
}

</style>
