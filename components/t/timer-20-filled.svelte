<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="crlgjcczw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:timer-20-filled" {...props}></Icon>
<style>
:global(.crlgjcczw) {
  fill: currentColor;
  d: path("M7 2.5a.5.5 0 0 1 .5-.5h4a.5.5 0 0 1 0 1h-4a.5.5 0 0 1-.5-.5m7.45 1.429a.5.5 0 0 1 .706 0l1.414 1.414a.5.5 0 1 1-.707.707L14.45 4.636a.5.5 0 0 1 0-.707M16.5 11a7 7 0 1 1-14 0a7 7 0 0 1 14 0M9 6.5v5a.5.5 0 0 0 1 0v-5a.5.5 0 0 0-1 0");
}

</style>
