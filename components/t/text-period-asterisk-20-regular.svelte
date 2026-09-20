<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hs7gaq0gg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-period-asterisk-20-regular" {...props}></Icon>
<style>
:global(.hs7gaq0gg) {
  fill: currentColor;
  d: path("M11.996 4.496a.5.5 0 0 0-1 0v2.465l-2.341-.76a.5.5 0 0 0-.31.95l2.345.762l-1.45 1.998a.5.5 0 1 0 .808.588l1.45-1.996l1.45 1.995a.5.5 0 0 0 .808-.587l-1.45-1.997l2.348-.762a.5.5 0 0 0-.309-.951l-2.349.763zM6 16a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

</style>
