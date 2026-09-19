<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a-a568vnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:x-server" {...props}></Icon>
<style>
:global(.a-a568vnm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.372 4.5v31.87l6.986-6.939L26.464 43.5l6.291-4.067l-6.889-12.897h9.762z");
}

</style>
