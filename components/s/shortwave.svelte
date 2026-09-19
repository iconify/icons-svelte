<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vivo2yiiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:shortwave" {...props}></Icon>
<style>
:global(.vivo2yiiy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 18.652c18.6 32.575 26.213-1.869 39 10.94c-21.055-33.378-24.021 2.356-39-10.94");
}

</style>
