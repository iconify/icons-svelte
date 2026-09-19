<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pi6ybkbni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-create-new-folder" {...props}></Icon>
<style>
:global(.pi6ybkbni) {
  fill: currentColor;
  d: path("M22 6H12l-2-2H2v16h20zm-3 8h-3v3h-2v-3h-3v-2h3V9h2v3h3z");
}

</style>
