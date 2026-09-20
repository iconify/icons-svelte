<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_a00mb8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:south-sharp" {...props}></Icon>
<style>
:global(.y_a00mb8o) {
  fill: currentColor;
  d: path("m12 22l-7-7l1.4-1.4l4.6 4.575V2h2v16.175l4.6-4.6L19 15z");
}

</style>
