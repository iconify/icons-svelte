<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s1sem7v0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:team-dashboard-sharp" {...props}></Icon>
<style>
:global(.s1sem7v0i) {
  fill: currentColor;
  d: path("M10.5 20v-7.75H4V20zm1 0H20v-7.75h-8.5zM4 11.25h16V4H4z");
}

</style>
