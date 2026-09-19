<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dbqlt-4fa"/><path class="o4-stt4zu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:wespo" {...props}></Icon>
<style>
:global(.dbqlt-4fa) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m39 37.5l4.5-27l-24.75 14.75z");
}

:global(.o4-stt4zu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9 37.5l-4.5-27l24.75 14.75z");
}

</style>
