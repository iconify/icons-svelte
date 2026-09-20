<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a6uifebpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:timer-2-sharp" {...props}></Icon>
<style>
:global(.a6uifebpi) {
  fill: currentColor;
  d: path("M8.5 18.116v-6.731h6.77v-4.27H8.5v-1.23h8v6.73H9.73v4.27h6.77v1.23z");
}

</style>
