<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="edq4z5z_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:yamiyami" {...props}></Icon>
<style>
:global(.edq4z5z_f) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21 28v11.5a3 3 0 1 0 6 0V25.242l14.621-14.62a3 3 0 0 0-4.242-4.243L19.758 24L6.378 10.621a3 3 0 0 1 4.243-4.242l11.38 11.379");
}

</style>
