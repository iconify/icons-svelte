<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tkh4i9boa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-italic-20-regular" {...props}></Icon>
<style>
:global(.tkh4i9boa) {
  fill: currentColor;
  d: path("M16 3a.5.5 0 0 1 0 1h-3.157L8.227 16H11.5a.5.5 0 0 1 0 1H4a.5.5 0 0 1 0-1h3.156l4.615-12H8.5a.5.5 0 0 1 0-1z");
}

</style>
