<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="af744looa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:x-twitter" {...props}></Icon>
<style>
:global(.af744looa) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.604 25.622L7.693 41.498M37.924 6.502L25.554 21.07M6.61 6.5l27.44 35h7.56l-27.439-35z");
}

</style>
