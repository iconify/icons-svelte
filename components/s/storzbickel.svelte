<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e-0yrmrat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:storzbickel" {...props}></Icon>
<style>
:global(.e-0yrmrat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.94 26.91H20.2l-6 16.31a21.64 21.64 0 0 1 0-38.44l6 16.31h7.62l6-16.31a21.64 21.64 0 0 1 0 38.44Z");
}

</style>
