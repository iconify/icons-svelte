<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h8odqzuek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:zlketang" {...props}></Icon>
<style>
:global(.h8odqzuek) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.15 5.5h20.74l-19.27 37m32.23 0H20.11l19.268-37");
}

</style>
