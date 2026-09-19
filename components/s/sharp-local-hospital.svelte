<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sajzmmbry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-local-hospital" {...props}></Icon>
<style>
:global(.sajzmmbry) {
  fill: currentColor;
  d: path("M21 3H3.01L3 21h18zm-3 11h-4v4h-4v-4H6v-4h4V6h4v4h4z");
}

</style>
