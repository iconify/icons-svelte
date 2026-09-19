<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pm_yd1ngh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:zorin-connect" {...props}></Icon>
<style>
:global(.pm_yd1ngh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.274 19.544H43.5v17.275H33.274zm8.725-8.364H9.579v25.64m-5.079 0h21.912");
}

</style>
