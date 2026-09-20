<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w0pukz8vh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:view-sidebar-sharp" {...props}></Icon>
<style>
:global(.w0pukz8vh) {
  fill: currentColor;
  d: path("M17 9V5h4v4zm0 5v-4h4v4zM3 19V5h13v14zm14 0v-4h4v4z");
}

</style>
