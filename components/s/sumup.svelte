<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ggv_6db4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:sumup" {...props}></Icon>
<style>
:global(.ggv_6db4v) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.23 28.604c-5.535-5.514-5.535-14.454 0-19.968s14.51-5.515 20.046 0zm-4.506 10.76c5.535 5.515 14.51 5.515 20.046 0s5.535-14.454 0-19.968z");
}

</style>
