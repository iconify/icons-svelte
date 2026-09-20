<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b783n6blg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:triangle-right-20-filled" {...props}></Icon>
<style>
:global(.b783n6blg) {
  fill: currentColor;
  d: path("M17.215 8.68c1.047.568 1.047 2.07 0 2.638l-11.999 6.5a1.5 1.5 0 0 1-2.214-1.32V3.5a1.5 1.5 0 0 1 2.214-1.32z");
}

</style>
