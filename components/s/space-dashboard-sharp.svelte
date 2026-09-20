<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ye3ydfbrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:space-dashboard-sharp" {...props}></Icon>
<style>
:global(.ye3ydfbrz) {
  fill: currentColor;
  d: path("M4 20V4h7.5v16zm8.5-9V4H20v7zm7.5 9h-7.5v-8H20z");
}

</style>
