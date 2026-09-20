<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gqmzf6wsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:text-format-outline" {...props}></Icon>
<style>
:global(.gqmzf6wsw) {
  fill: currentColor;
  d: path("M5 19v-2h14v2zm1.9-4L11 4h2l4.1 11h-1.9l-.95-2.8H9.8l-1 2.8zm3.45-4.4h3.3l-1.6-4.55h-.1z");
}

</style>
