<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o7ik_yyie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:toggle-left-20-filled" {...props}></Icon>
<style>
:global(.o7ik_yyie) {
  fill: currentColor;
  d: path("M14 6a4 4 0 0 1 0 8H6a4 4 0 0 1 0-8zm-8 6a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

</style>
