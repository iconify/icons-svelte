<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="zaa81lbmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:text-bolder-thin" {...props}></Icon>
<style>
:global(.zaa81lbmo) {
  fill: currentColor;
  d: path("M162.3 117.2A40 40 0 0 0 140 44H64a4.1 4.1 0 0 0-4 4v152a4 4 0 0 0 4 4h88a44 44 0 0 0 10.3-86.8ZM68 52h72a32 32 0 0 1 0 64H68Zm84 144H68v-72h84a36 36 0 0 1 0 72Z");
}

</style>
