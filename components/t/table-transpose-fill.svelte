<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zno1pmbbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:table-transpose-fill" {...props}></Icon>
<style>
:global(.zno1pmbbb) {
  fill: currentColor;
  d: path("M12 2h8a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2h-8a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2m-8 8h2a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2v-8a2 2 0 0 1 2-2m11 5v1.586l4.293-4.293a.999.999 0 1 1 1.414 1.414L16.414 18H18a1 1 0 0 1 0 2h-4a1 1 0 0 1-1-1v-4a1 1 0 0 1 2 0");
}

</style>
