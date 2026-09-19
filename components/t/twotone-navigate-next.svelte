<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_eprobji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-navigate-next" {...props}></Icon>
<style>
:global(.p_eprobji) {
  fill: currentColor;
  d: path("m10.02 18l6-6l-6-6l-1.41 1.41L13.19 12l-4.58 4.59z");
}

</style>
