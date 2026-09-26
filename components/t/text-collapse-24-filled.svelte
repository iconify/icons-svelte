<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhxd2m9zn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-collapse-24-filled" {...props}></Icon>
<style>
:global(.mhxd2m9zn) {
  fill: currentColor;
  d: path("M21 18a1 1 0 1 1 0 2H6a1 1 0 1 1 0-2zM6.5 7a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m-2 4a.5.5 0 0 0 0 1h4a.5.5 0 0 0 0-1zM21 13a1 1 0 1 1 0 2h-7a1 1 0 1 1 0-2zm0-5a1 1 0 1 1 0 2h-7a1 1 0 1 1 0-2zm0-5a1 1 0 1 1 0 2H6a1 1 0 0 1 0-2z");
}

</style>
