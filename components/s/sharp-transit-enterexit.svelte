<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d4sjqob7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-transit-enterexit" {...props}></Icon>
<style>
:global(.d4sjqob7l) {
  fill: currentColor;
  d: path("M16 18H6V8h3v4.77L15.98 6L18 8.03L11.15 15H16z");
}

</style>
