<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fl_go2b-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:speed-0-5-sharp" {...props}></Icon>
<style>
:global(.fl_go2b-w) {
  fill: currentColor;
  d: path("M7.75 16.5v-1h1v1zm2.5 0v-1h4v-3h-4v-5h5v1h-4v3h4v5z");
}

</style>
