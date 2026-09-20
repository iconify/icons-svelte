<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j3ej0_l5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:superscript-outline-sharp" {...props}></Icon>
<style>
:global(.j3ej0_l5t) {
  fill: currentColor;
  d: path("M19 9V6h3V5h-3V4h4v3h-3v1h3v1zM5.875 20l4.625-7.275L6.2 6h2.65l3.1 5h.1l3.075-5H17.8l-4.325 6.725L18.125 20H15.45l-3.4-5.425h-.1L8.55 20z");
}

</style>
