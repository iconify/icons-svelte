<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yk1uh2y2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:view-real-size-sharp" {...props}></Icon>
<style>
:global(.yk1uh2y2z) {
  fill: currentColor;
  d: path("M7 17V9H5V7h4v10zm4 0v-2h2v2zm5 0V9h-2V7h4v10zm-5-4v-2h2v2z");
}

</style>
