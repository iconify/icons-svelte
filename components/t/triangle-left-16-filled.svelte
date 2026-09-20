<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n13ecldkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:triangle-left-16-filled" {...props}></Icon>
<style>
:global(.n13ecldkm) {
  fill: currentColor;
  d: path("M1.777 9.313a1.5 1.5 0 0 1 0-2.629l9.999-5.5A1.5 1.5 0 0 1 13.999 2.5v10.999a1.5 1.5 0 0 1-2.223 1.314z");
}

</style>
