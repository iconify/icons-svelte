<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="swxmvqbju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:shieldt" {...props}></Icon>
<style>
:global(.swxmvqbju) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 43.5c1.693 0 15.274-7.782 15.274-16.966V6.504C35.267 6.503 24 4.5 24 4.5S12.723 6.503 8.727 6.503v20.03C8.727 35.719 22.307 43.5 24 43.5m-6.467-30.263h12.934m-6.345 19.524V13.237");
}

</style>
