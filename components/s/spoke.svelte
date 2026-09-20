<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pp1ko9e5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:spoke" {...props}></Icon>
<style>
:global(.pp1ko9e5r) {
  fill: currentColor;
  d: path("M12 10q-1.237 0-2.119-.881T9 7t.881-2.119T12 4t2.119.881T15 7t-.881 2.119T12 10M7 20q-1.237 0-2.119-.881T4 17t.881-2.119T7 14t2.119.881T10 17t-.881 2.119T7 20m10 0q-1.237 0-2.119-.881T14 17t.881-2.119T17 14t2.119.881T20 17t-.881 2.119T17 20");
}

</style>
