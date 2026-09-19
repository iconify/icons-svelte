<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lvj1aul1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:videoland" {...props}></Icon>
<style>
:global(.lvj1aul1a) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 40.878L43.5 7.122H32.199L24 22.824L15.801 7.122H4.5z");
}

</style>
