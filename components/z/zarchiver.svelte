<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="js2i01-yx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:zarchiver" {...props}></Icon>
<style>
:global(.js2i01-yx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.89 7.05h23.53l-11 25.42h13.17L34.26 41H4.51l11-25.42h-5zm23.53 0L43.51 41h-9.25L24 17.25");
}

</style>
