<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i48s61ajx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:search-info-24-regular" {...props}></Icon>
<style>
:global(.i48s61ajx) {
  fill: currentColor;
  d: path("M16.102 17.162a8 8 0 1 1 1.06-1.06l4.618 4.618a.75.75 0 1 1-1.06 1.06zM17.5 11a6.5 6.5 0 1 0-13 0a6.5 6.5 0 0 0 13 0M11 10a.75.75 0 0 1 .75.75v3.5a.75.75 0 0 1-1.5 0v-3.5A.75.75 0 0 1 11 10m0-1.5a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

</style>
