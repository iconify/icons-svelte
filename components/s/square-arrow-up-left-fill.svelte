<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n87b57b5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-arrow-up-left-fill" {...props}></Icon>
<style>
:global(.n87b57b5u) {
  fill: currentColor;
  d: path("M2 5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm11 5a1 1 0 0 0 0-2H9a1 1 0 0 0-1 1v4a1 1 0 0 0 2 0v-1.586l4.293 4.293a.999.999 0 1 0 1.414-1.414L11.414 10Z");
}

</style>
