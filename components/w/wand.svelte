<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e92gzlzeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:wand" {...props}></Icon>
<style>
:global(.e92gzlzeo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.5 8.13l10.28 28.11l9.27-28.11l9.24 28.13L43.5 8.33m-39 31.54h39");
}

</style>
