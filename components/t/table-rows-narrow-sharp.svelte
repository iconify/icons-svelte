<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bhlc2hb4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:table-rows-narrow-sharp" {...props}></Icon>
<style>
:global(.bhlc2hb4h) {
  fill: currentColor;
  d: path("M4 15.635h16V12.5H4zM4 11.5h16V8.366H4zm0-4.134h16V4.23H4zM20 20V4zm-16-.23h16v-3.136H4z");
}

</style>
