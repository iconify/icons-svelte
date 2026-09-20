<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k63xtibdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:tablet-32-filled" {...props}></Icon>
<style>
:global(.k63xtibdz) {
  fill: currentColor;
  d: path("M2 8.25A3.25 3.25 0 0 1 5.25 5h21.5A3.25 3.25 0 0 1 30 8.25v15.5A3.25 3.25 0 0 1 26.75 27H5.25A3.25 3.25 0 0 1 2 23.75zM13 21a1 1 0 1 0 0 2h6a1 1 0 1 0 0-2z");
}

</style>
