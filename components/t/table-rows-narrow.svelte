<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lkot58gix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:table-rows-narrow" {...props}></Icon>
<style>
:global(.lkot58gix) {
  fill: currentColor;
  d: path("M4 15.635V12.5h16v3.135zM4 11.5V8.366h16V11.5zm0-4.134V4.23h16v3.135zm0 12.403v-3.134h16v3.134z");
}

</style>
