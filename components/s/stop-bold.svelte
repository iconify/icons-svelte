<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="swhg0xjgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:stop-bold" {...props}></Icon>
<style>
:global(.swhg0xjgr) {
  fill: currentColor;
  d: path("M200 36H56a20 20 0 0 0-20 20v144a20 20 0 0 0 20 20h144a20 20 0 0 0 20-20V56a20 20 0 0 0-20-20m-4 160H60V60h136Z");
}

</style>
