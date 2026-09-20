<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sligubb6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:view-list-sharp" {...props}></Icon>
<style>
:global(.sligubb6p) {
  fill: currentColor;
  d: path("M9 20h13v-4H9zM2 8h5V4H2zm0 6h5v-4H2zm0 6h5v-4H2zm7-6h13v-4H9zm0-6h13V4H9z");
}

</style>
