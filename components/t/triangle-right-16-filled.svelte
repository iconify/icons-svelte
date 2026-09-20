<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n6xnqrb5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:triangle-right-16-filled" {...props}></Icon>
<style>
:global(.n6xnqrb5t) {
  fill: currentColor;
  d: path("M14.222 6.687a1.5 1.5 0 0 1 0 2.629l-10 5.499A1.5 1.5 0 0 1 2 13.5V2.502a1.5 1.5 0 0 1 2.223-1.314z");
}

</style>
