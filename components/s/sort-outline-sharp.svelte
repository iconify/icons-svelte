<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cui83ccbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:sort-outline-sharp" {...props}></Icon>
<style>
:global(.cui83ccbj) {
  fill: currentColor;
  d: path("M4 17v-1h4.75v1zm0-4.5v-1h10.366v1zM4 8V7h16v1z");
}

</style>
