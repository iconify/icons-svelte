<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uz07ck55l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:sams-club" {...props}></Icon>
<style>
:global(.uz07ck55l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.991 40.491L5.5 24L21.991 7.509m4.018 32.982L42.5 24L26.009 7.509");
}

</style>
