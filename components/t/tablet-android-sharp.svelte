<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c9j5hbbqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:tablet-android-sharp" {...props}></Icon>
<style>
:global(.c9j5hbbqz) {
  fill: currentColor;
  d: path("M3 23V1h18v22zm7-3h4v-1h-4zm-5-4h14V6H5z");
}

</style>
