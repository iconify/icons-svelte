<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wybgtqyaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:triangle-down-32-filled" {...props}></Icon>
<style>
:global(.wybgtqyaq) {
  fill: currentColor;
  d: path("M13.15 27.319c1.236 2.242 4.457 2.242 5.693 0l10.75-19.498c1.194-2.166-.373-4.819-2.846-4.819H5.255c-2.473 0-4.04 2.652-2.847 4.818z");
}

</style>
