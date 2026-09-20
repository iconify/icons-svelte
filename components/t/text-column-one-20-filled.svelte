<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="prt2dfblb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-column-one-20-filled" {...props}></Icon>
<style>
:global(.prt2dfblb) {
  fill: currentColor;
  d: path("M15 5.75a.75.75 0 0 0-.75-.75h-8.5a.75.75 0 0 0 0 1.5h8.5a.75.75 0 0 0 .75-.75m0 3a.75.75 0 0 0-.75-.75h-8.5a.75.75 0 0 0 0 1.5h8.5a.75.75 0 0 0 .75-.75m0 3a.75.75 0 0 0-.75-.75h-8.5a.75.75 0 0 0 0 1.5h8.5a.75.75 0 0 0 .75-.75m0 3a.75.75 0 0 0-.75-.75h-8.5a.75.75 0 0 0 0 1.5h8.5a.75.75 0 0 0 .75-.75");
}

</style>
