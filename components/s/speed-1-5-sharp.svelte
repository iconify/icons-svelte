<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="an7cilupt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:speed-1-5-sharp" {...props}></Icon>
<style>
:global(.an7cilupt) {
  fill: currentColor;
  d: path("M7 17V9H5V7h4v10zm3 0v-2h2v2zm3 0v-2h4v-2h-4V7h6v2h-4v2h4v6z");
}

</style>
