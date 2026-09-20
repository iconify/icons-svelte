<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p74p68bjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:shape-union-20-filled" {...props}></Icon>
<style>
:global(.p74p68bjk) {
  fill: currentColor;
  d: path("M4.5 2A2.5 2.5 0 0 0 2 4.5v6A2.5 2.5 0 0 0 4.5 13H7v2.5A2.5 2.5 0 0 0 9.5 18h6a2.5 2.5 0 0 0 2.5-2.5v-6A2.5 2.5 0 0 0 15.5 7H13V4.5A2.5 2.5 0 0 0 10.5 2z");
}

</style>
