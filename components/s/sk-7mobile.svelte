<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="svte6bb6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:sk-7mobile" {...props}></Icon>
<style>
:global(.svte6bb6c) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.643 17.133H10.786L5.501 7.978L42.5 7.98L24 40.022l-5.286-9.155z");
}

</style>
