<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="btncfkbgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:thelife" {...props}></Icon>
<style>
:global(.btncfkbgf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.5 41.875l17.469-9.75v-16.25h-6.5v-4.062h6.5V6.125h4.062v5.688h6.5v4.062h-6.5v16.25l17.469 9.75");
}

</style>
