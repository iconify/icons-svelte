<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ykbq6tbjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:streamlabs" {...props}></Icon>
<style>
:global(.ykbq6tbjt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.316 14.25h18.672a6.51 6.51 0 0 1 6.512 6.512v13.78a6.51 6.51 0 0 1-6.512 6.511H15.71a3.907 3.907 0 0 1-3.908-3.907V20.762a6.51 6.51 0 0 1 6.512-6.512m7.22 12.051v7.011m8.91-7.011v7.011M19.107 6.947A14.607 14.607 0 0 0 4.5 21.553");
}

</style>
