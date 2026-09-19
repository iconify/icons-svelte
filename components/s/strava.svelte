<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ei45heb_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:strava" {...props}></Icon>
<style>
:global(.ei45heb_l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.016 26.855L19.839 4.5L8.661 26.855m14.033 0L31.016 43.5l8.323-16.645");
}

</style>
