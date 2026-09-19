<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r19scibji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:upgrado" {...props}></Icon>
<style>
:global(.r19scibji) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m10.313 21.744l29.325.023l-1.989 4.091l-29.385.093zM6.547 30.82l29.327.022l-1.99 4.091l-29.384.093zm7.628-17.846l29.325.023l-1.988 4.09l-29.387.093z");
}

</style>
