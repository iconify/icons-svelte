<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qk1bq_b-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:watertracker" {...props}></Icon>
<style>
:global(.qk1bq_b-o) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.5c0 3.945-12 13.717-12 27.405A11.803 11.803 0 0 0 24 43.5a11.803 11.803 0 0 0 12-11.595C36 18.217 24 8.445 24 4.5");
}

</style>
