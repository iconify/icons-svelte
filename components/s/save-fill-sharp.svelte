<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="khhuouisa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:save-fill-sharp" {...props}></Icon>
<style>
:global(.khhuouisa) {
  fill: currentColor;
  d: path("M18 22v-8a1 1 0 0 0-1-1H7a1 1 0 0 0-1 1v8H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1h14c.265 0 .52.105.707.293l4 4A1 1 0 0 1 22 7v14a1 1 0 0 1-1 1ZM15 6H9a1 1 0 0 0 0 2h6a1 1 0 0 0 0-2M8 22v-7h8v7Z");
}

</style>
