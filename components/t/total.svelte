<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dtbr53lgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:total" {...props}></Icon>
<style>
:global(.dtbr53lgc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 8.832h-37l4.986 8.761h8.341v13.374L24 39.168l5.172-8.201V17.593h8.342z");
}

</style>
