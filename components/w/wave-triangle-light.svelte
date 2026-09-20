<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="msdpiacfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:wave-triangle-light" {...props}></Icon>
<style>
:global(.msdpiacfb) {
  fill: currentColor;
  d: path("m236.86 131.51l-52 72a6 6 0 0 1-9.72 0L76 66.25l-47.14 65.26a6 6 0 1 1-9.72-7l52-72a6 6 0 0 1 9.72 0L180 189.75l47.14-65.26a6 6 0 0 1 9.72 7Z");
}

</style>
