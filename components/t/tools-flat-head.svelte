<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fyoz_3bhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:tools-flat-head" {...props}></Icon>
<style>
:global(.fyoz_3bhp) {
  fill: currentColor;
  d: path("M8.866 20v-1h6.269v1zm0-2l-.847-5.942L9.79 5h4.423l1.769 7.058L15.135 18zm.319-6.5h5.63L13.45 6h-2.9z");
}

</style>
