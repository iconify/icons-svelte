<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ye5chmwxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:shuffle-on-sharp" {...props}></Icon>
<style>
:global(.ye5chmwxn) {
  fill: currentColor;
  d: path("M1 23V1h22v22zm13-3h6v-6h-2v2.55l-3.15-3.15l-1.425 1.425L16.6 18H14zm-8.6 0L18 7.4V10h2V4h-6v2h2.6L4 18.6zm3.775-9.425l1.4-1.4L5.4 4L4 5.4z");
}

</style>
