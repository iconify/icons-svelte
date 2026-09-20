<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="sdd03o8jg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noto-v1:white-medium-square" {...props}></Icon>
<style>
:global(.sdd03o8jg) {
  fill: var(--svg-color--e0e0e0, #e0e0e0);
  d: path("M23 23h82v82H23z");
}

</style>
