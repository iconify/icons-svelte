<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wi1156b9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-open-in-browser" {...props}></Icon>
<style>
:global(.wi1156b9i) {
  fill: currentColor;
  d: path("M3 4v16h6v-2H5V8h14v10h-4v2h6V4zm9 6l-4 4h3v6h2v-6h3z");
}

</style>
