<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r7rs0obbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:security-update-good-sharp" {...props}></Icon>
<style>
:global(.r7rs0obbo) {
  fill: currentColor;
  d: path("m11.05 15l-2.8-2.8l1.4-1.4l1.4 1.4l3.55-3.55l1.4 1.4zM5 23V1h14v22zm2-5h10V6H7z");
}

</style>
