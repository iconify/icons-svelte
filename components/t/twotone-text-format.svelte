<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ewoqmb5xl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-text-format" {...props}></Icon>
<style>
:global(.ewoqmb5xl) {
  fill: currentColor;
  d: path("M5 17v2h14v-2zm4.5-4.2h5l.9 2.2h2.1L12.75 4h-1.5L6.5 15h2.1zM12 5.98L13.87 11h-3.74z");
}

</style>
