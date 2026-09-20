<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="zbu7n5o_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:subset-of-thin" {...props}></Icon>
<style>
:global(.zbu7n5o_d) {
  fill: currentColor;
  d: path("M204 208a4 4 0 0 1-4 4H48a4 4 0 0 1 0-8h152a4 4 0 0 1 4 4m-4-44h-96a52 52 0 0 1 0-104h96a4 4 0 0 0 0-8h-96a60 60 0 0 0 0 120h96a4 4 0 0 0 0-8");
}

</style>
