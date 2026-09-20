<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="alppr7vxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:speaker-3-sharp" {...props}></Icon>
<style>
:global(.alppr7vxf) {
  fill: currentColor;
  d: path("M8.692 21v-1H4.981V3H19v17h-3.73v1z");
}

</style>
