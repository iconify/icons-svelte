<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7ual1e1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-title" {...props}></Icon>
<style>
:global(.t7ual1e1t) {
  fill: currentColor;
  d: path("M5 7h5.5v12h3V7H19V4H5z");
}

</style>
